# Vault RAG — Offline Multimodal Retrieval System

**Smart India Hackathon 2025 · Problem Statement SIH25231**
**Theme: Smart Automation · Team: Quantum Ledgers**

An offline, privacy-first multimodal RAG (Retrieval-Augmented Generation)
system that can ingest, index and query documents, images and audio
without any internet connection or cloud dependency.

---

## The Problem

Sensitive environments like defence, healthcare and legal sectors
cannot send data to cloud APIs for AI processing.
Existing RAG systems require internet. There was no secure,
offline alternative that worked across multiple data formats.

---

## Our Solution — Vault RAG
User Query
↓
Ingestion Module (PDF / Image / Audio)
↓
Embedding Generation (CLIP + Whisper ASR)
↓
FAISS Vector Index
↓
LLM-RAG Response with Citations (Qwen 2.5 + LangChain)
↓
Chat Interface with Grounded Answers

---

## Key Features

| Feature | How |
|--------|-----|
| Offline operation | No cloud API calls at any stage |
| Audio to text | OpenAI Whisper ASR runs locally |
| Unified search | CLIP embeddings across text, image, audio |
| Fast retrieval | FAISS approximate nearest-neighbour search |
| Grounded answers | Citations with page/timestamp/image ID |
| Secure backend | FastAPI with encrypted storage and audit logs |

---

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)

**Models & Libraries:** CLIP · Whisper ASR · FAISS · BGE-EN-ICL · Qwen 2.5-7B · LangChain · ChromaDB

---

## My Contribution

- Problem statement research and framing
- Solution architecture ideation
- PPT development and presentation design
- Feasibility and risk analysis documentation

---









