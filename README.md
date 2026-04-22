# 📄 PDF Summarizer + RAG Chatbot

> AI-powered application that summarizes PDF documents and enables context-aware question answering using Retrieval-Augmented Generation (RAG).

---

## 🎯 Problem

Reading and extracting insights from long PDFs (research papers, reports, documentation) is time-consuming and inefficient.

---

## 💡 Solution

This project provides:
- Automatic PDF text extraction and summarization  
- Context-aware Q&A using RAG (Retrieval-Augmented Generation)  
- Source-grounded answers with relevant document chunks  

---

## ⚙️ Features

- 📄 Upload PDF and extract structured text  
- ✂️ Generate concise summaries using transformer models  
- 🤖 Ask questions → get context-aware answers  
- 📚 Retrieve relevant document chunks using vector search  
- 🔁 Multi-turn conversational support (if implemented)  

---

## 🧠 Architecture

```text
PDF → Text Extraction → Chunking → Embeddings → Vector DB
                                             ↓
User Query → Retriever → LLM → Response (with context)
