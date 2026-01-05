# 🤖 RAG Chatbot (AI)

This project implements a **Retrieval-Augmented Generation (RAG) Chatbot** capable of answering questions using information retrieved from external documents (PDF´s manuals and guides), combining semantic search with large language models.

The goal of this project is to demonstrate an end-to-end **RAG pipeline**, from document ingestion to accurate, context-aware answer generation.

---

## 🧠 Project Overview
This chatbot:
- Loads external documents (PDF / text)
- Splits documents into manageable chunks
- Generates semantic embeddings
- Stores embeddings in a vector database
- Retrieves the most relevant chunks for a given query
- Images recognizition sended by the user
- Similarity search
- Generates responses using a Large Language Model (LLM)

This approach helps reduce hallucinations and improves factual accuracy.

---

## ⚙️ Technologies Used
- Python 3.x
- Jupyter Notebook
- LangChain
- FAISS (Vector Database)
- OpenAI / LLM API

---

