# 📺 YouTube Chatbot – RAG-Based Question Answering System

This project allows users to interact with any YouTube video by simply entering the video ID. The chatbot uses a Retrieval-Augmented Generation (RAG) pipeline to extract the transcript, chunk it semantically, and generate intelligent answers to queries or summaries using a Large Language Model (LLM).

---

## 🚀 Features

- 🔍 Ask questions like:
  - “Is [topic] discussed in this video?”
  - “What are the key takeaways?”
  - “Summarize this video in 10 bullet points.”
- 🎯 Built using:
  - LangChain for RAG and agent workflow
  - FAISS for vector search
  - OpenAI LLMs for dynamic response generation
- 📄 Transcript extraction from YouTube videos
- 🔗 Seamless querying with natural language prompts

---

## 🛠 Tech Stack

- **Python**
- **LangChain**
- **OpenAI API**
- **FAISS**
- **Streamlit**
- **YouTube Transcript API**

---

## 📦 How It Works

1. The user inputs a YouTube video ID.
2. The video transcript is fetched using the YouTube Transcript API.
3. The transcript is split into semantically meaningful chunks.
4. Embeddings are generated and stored in FAISS.
5. When a query is submitted, relevant chunks are retrieved and passed into an LLM for a final answer.

---

## 🔗 Run on Google Colab

https://colab.research.google.com/drive/1VBD9Aaxsd4_10zsFfs6CGA1sGyngDtC6?usp=sharing

---

## 📁 Files

- `youtube_chatbot.ipynb` – Main Colab notebook
- `README.md` – This file
- `requirements.txt` – Python dependencies (optional)

---

## ✅ Requirements

To run locally or replicate in another environment:

```bash
pip install langchain faiss-cpu openai streamlit youtube-transcript-api
