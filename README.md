# Enterprise Search System

An end-to-end, production-oriented enterprise search and Retrieval-Augmented Generation (RAG) system designed to retrieve relevant information from internal company documents and generate accurate, evidence-grounded answers with verifiable citations.

The goal is to build a reliable enterprise search application that combines semantic search, keyword retrieval, hybrid ranking, reranking, and citation validation.

## Project Objectives

- Build a document ingestion and parsing pipeline.
- Implement intelligent chunking with metadata preservation.
- Combine semantic search with BM25 keyword retrieval.
- Improve retrieval quality through hybrid search and cross-encoder reranking.
- Generate context-grounded answers using an LLM.
- Provide verifiable citations linked to retrieved evidence.
- Support metadata filtering and document-level access control.
- Evaluate retrieval quality, answer faithfulness, and citation correctness.
- Develop an API and web interface.
- Containerize the application using Docker.

## Planned Technology Stack

| Component | Technology |
|---|---|
| Language | Python |
| Backend API | FastAPI |
| Frontend | Streamlit |
| Embeddings | Sentence Transformers |
| Keyword Retrieval | BM25 |
| Vector Search | Qdrant / FAISS |
| Hybrid Retrieval | BM25 + Vector Search |
| Reranking | Cross-Encoder |
| Answer Generation | Open-Weight LLM / API-Based Model |
| Evaluation | Recall@K, MRR, nDCG, Faithfulness, Citation Correctness |
| Containerization | Docker |