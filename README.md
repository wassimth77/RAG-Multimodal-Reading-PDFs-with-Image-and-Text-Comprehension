# Multimodal RAG System with BART

## Description

This project implements a **multimodal Retrieval-Augmented Generation (RAG) system** using **BART** from Hugging Face. The system can ingest PDF documents containing **text and images**, build embeddings for both modalities, and answer questions using a **context-aware generative model**.

The pipeline consists of:

1. **PDF Extraction**: Extracts text and images from PDFs.
2. **Embedding Construction**: Uses **CLIP** for both text and image embeddings.
3. **Vector Store**: Stores embeddings using **FAISS** for efficient similarity search.
4. **Generative Model**: Uses **BART** to generate concise, context-aware answers.
5. **Interactive Interface**: Allows users to ask questions interactively or query specific documents.

This system is useful for extracting insights from reports, academic papers, or any document with mixed content.

---

## Features

- Supports **text and image embeddings**.
- **FAISS-powered vector search** for efficient retrieval.
- Generates answers in **French** based on the retrieved context.
- **Interactive chat mode** for querying PDFs.
- Caching of embeddings for faster repeated runs.
- Works locally or in **Google Colab**.

---

## Installation

1. Clone this repository:

```bash
git clone https://github.com/yourusername/multimodal-rag-bart.git
cd multimodal-rag-bart
