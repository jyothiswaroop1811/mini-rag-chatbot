# Mini RAG Chatbot

## Overview

This project is a simple Retrieval-Augmented Generation (RAG) chatbot built using Python.
The chatbot reads a PDF document, extracts its content, stores semantic embeddings in a vector database, and answers user questions based on the document content.

The project demonstrates the complete RAG pipeline including:

* PDF text extraction
* Text chunking
* Embedding generation
* Vector database creation
* Semantic search
* Context retrieval
* LLM-based answer generation

---

# Project Structure

```bash
mini-rag-chatbot/
│
├── Mini_RAG_Chatbot.ipynb
├── README.md
├── requirements.txt
├── sample_data/
│   └── sample.pdf
├── screenshots/
```

---

# Technologies Used

* Python
* Jupyter Notebook
* LangChain
* Sentence Transformers
* FAISS
* HuggingFace Transformers
* PyPDF

---

# Libraries Used

```python
pypdf
langchain
sentence-transformers
faiss-cpu
transformers
torch
numpy
```

---

# Features

* Reads PDF documents
* Extracts text from PDF
* Splits text into smaller chunks
* Converts chunks into embeddings
* Stores embeddings using FAISS vector database
* Retrieves relevant chunks using semantic similarity
* Uses an LLM to generate answers
* Supports repeated question answering through chat loop

---

# RAG Pipeline

```text
PDF Document
     ↓
Text Extraction
     ↓
Chunking
     ↓
Embedding Generation
     ↓
FAISS Vector Storage
     ↓
User Question
     ↓
Question Embedding
     ↓
Semantic Search
     ↓
Relevant Context Retrieval
     ↓
LLM Prompting
     ↓
Final Answer
```

---

# Installation

## Step 1: Clone Repository

```bash
git clone <your-github-repository-link>
```

---

## Step 2: Install Required Libraries

```bash
pip install -r requirements.txt
```

---

# How to Run

1. Open `Mini_RAG_Chatbot.ipynb`
2. Run all notebook cells sequentially
3. Place your PDF inside:

```bash
sample_data/sample.pdf
```

4. Ask questions in the chatbot loop
5. Type `exit` to stop the chatbot

---

# Sample Questions

* What are input devices?
* Explain computer hardware.
* What is the function of a mouse?
* Define software.

---

# Key Concepts Learned

* Retrieval-Augmented Generation (RAG)
* Embeddings
* Vector Databases
* Semantic Search
* Prompt Engineering
* PDF Processing
* LLM-based Question Answering

---

# Challenges Faced

* Handling noisy PDF text extraction
* Managing chunk sizes
* Improving retrieval quality
* Handling incomplete LLM responses

---

# Future Improvements

* Add Streamlit UI
* Support multiple PDFs
* Add conversational memory
* Use ChromaDB
* Improve prompt engineering
* Add citation-based answers

---

# Conclusion

This project successfully implements a complete beginner-friendly RAG chatbot pipeline using open-source tools and models.
It demonstrates how external document knowledge can be combined with Large Language Models to build intelligent question-answering systems.

---
