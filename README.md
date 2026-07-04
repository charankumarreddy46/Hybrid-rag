# Production-Grade Hybrid RAG System

## Overview

This project is a **Production-Grade Hybrid Retrieval-Augmented Generation (RAG) System** designed to answer user questions accurately using information extracted from uploaded PDF documents. Instead of relying only on the Large Language Model's internal knowledge, the system retrieves relevant document content, reranks the retrieved results, and generates grounded answers based on the uploaded knowledge base.

The system follows a modular architecture built with **LangChain**, making it scalable, maintainable, and suitable for real-world applications.

## Features

* Upload and process PDF documents
* Intelligent document understanding and preprocessing
* Adaptive document chunking
* Semantic embeddings using Hugging Face/OpenAI embeddings
* FAISS vector database for fast similarity search
* BM25 keyword-based retrieval
* Hybrid Retrieval (BM25 + FAISS)
* Cross-Encoder reranking for improved relevance
* Context-aware answer generation
* Source-aware responses from uploaded documents
* Modular and production-ready architecture

## Architecture

### Phase 1 – Data Pipeline

* Document Ingestion
* Document Understanding
* Adaptive Chunking
* Embeddings
* Indexing
* FAISS Vector Database

### Phase 2 – Retrieval Pipeline

* Query Processing
* Hybrid Retrieval (BM25 + FAISS)
* Cross-Encoder Reranking
* Context Builder
* Large Language Model (LLM)
* Answer / Result

## Technology Stack

* Python
* LangChain
* FAISS
* BM25
* Hugging Face Embeddings
* BGE Cross-Encoder Reranker
* FastAPI
* React
* Groq / Gemini / OpenAI

## Project Goal

The objective of this project is to build a scalable and production-ready Hybrid RAG system that demonstrates modern document retrieval, semantic search, and grounded question answering techniques. It serves as a foundation for advanced systems such as Agentic RAG, Graph RAG, and Enterprise AI Assistants.
