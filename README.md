# RAG Basics – Retrieval-Augmented Generation

A hands-on project exploring the fundamentals of **Retrieval-Augmented Generation (RAG)** using Python, LangChain, FAISS, HuggingFace Embeddings and Groq LLM.

The project demonstrates how to build a basic RAG pipeline that retrieves relevant information from external documents and uses a Large Language Model (LLM) to generate context-aware responses.

## 🚀 Overview

Large Language Models can sometimes generate incorrect information or lack access to specific external knowledge.

Retrieval-Augmented Generation (RAG) addresses this by retrieving relevant information from a knowledge source and providing it as context to an LLM before generating an answer.

This project focuses on understanding each component of the RAG pipeline, from document ingestion to response generation.

## 🧠 Concepts Covered

- **Document Loading:** Loading documents using LangChain document loaders.
- **Text Splitting:** Breaking large documents into smaller chunks.
- **Embeddings:** Converting text into numerical vector representations.
- **Vector Database:** Storing and managing embeddings using FAISS.
- **Similarity Search:** Finding relevant document chunks based on semantic similarity.
- **Retrievers:** Retrieving relevant context for user queries.
- **LLM Integration:** Using Groq to generate natural language responses.
- **RAG Pipeline:** Connecting retrieval and generation into a single workflow.

## ⚙️ Technology Stack

| Technology | Purpose |
|---|---|
| Python | Programming language |
| LangChain | RAG application framework |
| FAISS | Vector storage and similarity search |
| HuggingFace | Text embeddings |
| Groq | LLM inference |
| Google Colab / Jupyter | Development and experimentation |

## 🔄 RAG Workflow

```text
Documents
    |
    v
Document Loading
    |
    v
Text Splitting
    |
    v
Generate Embeddings
    |
    v
Store in FAISS
    |
    v
User Query
    |
    v
Similarity Search
    |
    v
Retrieve Relevant Context
    |
    v
Groq LLM
    |
    v
Context-Aware Answer
```

## 📚 Understanding RAG

The basic RAG architecture consists of two major stages:

### 1. Retrieval

- Load external documents.
- Split documents into manageable chunks.
- Generate embeddings for each chunk.
- Store embeddings in a vector database.
- Retrieve relevant chunks based on the user's query.

### 2. Generation

- Pass the retrieved context and user query to the LLM.
- Generate an answer using the provided context.
- Return a natural language response.

## 🛠️ Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/rag-basics.git
cd rag-basics
```

Create a virtual environment:

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## 🔑 Environment Variables

Create a `.env` file in the project root:

```env
GROQ_API_KEY=your_groq_api_key
```

Never commit your actual API keys to GitHub.

## 🎯 Learning Objective

The main objective of this project is to develop a strong understanding of RAG architecture and its individual components before moving towards advanced applications such as:

- Document Question Answering
- Knowledge Base Assistants
- Enterprise RAG Systems
- Data Analytics Assistants
- Multi-document Retrieval Systems

## 📌 Project Status

**Learning and experimentation in progress.**

This repository serves as a foundation for exploring advanced RAG techniques and building more practical AI-powered applications.

---

**Built while learning Generative AI, LangChain and Retrieval-Augmented Generation.**
