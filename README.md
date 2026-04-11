<div align="center">
  
# 🚀 RAG Pipelines 

*My personal playground for exploring Retrieval-Augmented Generation (RAG), Vector Databases, and LLM Orchestration.*

[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://python.org)
[![LangChain](https://img.shields.io/badge/🦜_LangChain-Framework-green.svg)](https://langchain.com/)
[![ChromaDB](https://img.shields.io/badge/ChromaDB-Vector_Store-blueviolet.svg)](https://trychroma.com/)
[![Typesense](https://img.shields.io/badge/Typesense-Search_Engine-orange.svg)](https://typesense.org/)

</div>

---

## 📖 Overview

Welcome to my **RAG Pipelines**  repository! 

This repository contains my hands-on experiments and implementations of RAG workflows. Here, I'm exploring how to natively ingest documents, generate embeddings, and build robust search & retrieval pipelines using some of the most popular tools in the AI ecosystem today.

> [!NOTE]  
> This is a practice repository built for self-learning, debugging, and exploration of modern NLP, Vector Storage, and Large Language Model integrations.

---

## 🗂️ What's Inside?

### 📓 Jupyter Notebooks
- **`Ingestion.ipynb`** 🔍  
  The core notebook demonstrating how to parse PDF documents (like complex Neural Network research papers) using `PyMuPDFLoader`. It covers crucial steps like semantic text chunking, calculating vector embeddings via `sentence-transformers`, seamlessly pushing data into **ChromaDB**, and measuring document relevance with cosine similarity.
  
- **`tyepesense.ipynb`** ⚡  
  A playground notebook dedicated to integrating and evaluating **Typesense**—a blazingly fast and typo-tolerant search engine optimized for hybrid and vector-based AI retrieval.

### 💾 Data & Resources
- **`data/`**: The folder containing raw input documents, primarily PDF research papers.
- **`books.jsonl`**: A structured sample dataset of books used to study and test large-scale batch ingestion.
- **`test.txt`**: A foundational sample file discussing the impact and architecture of Artificial Intelligence, perfect for running small-scale debugging tests.

---

## 🛠️ Tech Stack

I'm currently playing around with:

| Category | Technologies |
| :--- | :--- |
| **LLM Orchestration** | LangChain (Core/Community/OpenAI/Groq), LangGraph |
| **Vector Databases** | ChromaDB, FAISS, Typesense |
| **Embeddings** | Hugging Face (`sentence-transformers`) |
| **Document Processing** | PyMuPDF, PyPDF |
| **Models** | OpenAI, Groq |

---

## ⚙️ Setup & Installation

If you'd like to spin this up locally and experiment alongside me, follow these steps:

**1. Clone the repository**
```bash
git clone <your-repo-link>
cd RAG-Pipelines
```

**2. Set up an isolated Python environment**
```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

**3. Configure Environment Variables**
Create a `.env` file in the root directory to store your sensitive API keys securely:
```ini
OPENAI_API_KEY=sk-...
GROQ_API_KEY=gsk-...
```

---

## 🚀 Usage

Launch your local Jupyter environment:
```bash
jupyter notebook
```

- Dive into [`Ingestion.ipynb`](./Ingestion.ipynb) to see the full RAG document chunking and vector storage flow.
- Open [`tyepesense.ipynb`](./tyepesense.ipynb) to test out advanced search operations with custom data.

---
<div align="center">
  <i>Happy coding and experimenting! 🧠✨</i>
</div>
