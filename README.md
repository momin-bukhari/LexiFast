# 🚀 LexiFast – Scalable Search Engine

LexiFast is a high-performance search engine designed to efficiently index and retrieve large-scale academic datasets. Built using core Data Structures & Algorithms concepts, the system processes **70,000+ research papers** from the ArXiv dataset and delivers **sub-second query responses**.

---

## 📌 Overview

LexiFast demonstrates the practical application of DSA in real-world systems. It uses advanced indexing techniques and optimized data structures to enable fast, scalable, and intelligent search.

Key highlights:
- ⚡ Sub-second search performance
- 📚 120,000+ unique words indexed
- 📄 5.4M+ total indexed hits
- 🔍 Smart query processing with ranking & proximity scoring
- 🔄 Incremental indexing (dynamic content addition)

---

## 🧠 Core Features

### 🔎 Efficient Search Engine
- Supports single-word and multi-word queries
- Boolean AND/OR query processing
- Proximity-based ranking for relevance

### 📚 Advanced Indexing
- Forward Index (Doc → Words)
- Inverted Index (Word → Docs)
- Barrel Partitioning for scalable storage

### ⚡ Autocomplete System
- Trie-based prefix search
- Real-time suggestions under 100ms

### 🔄 Incremental Indexing
- Add new documents without rebuilding the entire index
- Uses worker threads for parallel processing

### 🧠 Semantic Query Expansion
- Enhances search by including related terms (synonyms)

---

## 🏗️ Tech Stack

### 💻 Backend
- Node.js
- JavaScript
- Data Structures:
  - Hash Maps (Map)
  - Sets
  - Arrays
  - Trie (Prefix Tree)

### 🌐 Frontend
- React
- Vite

### ☁️ Deployment
- Backend: Microsoft Azure
- Frontend: Vercel

---

## ⚙️ System Architecture

LexiFast follows a modular pipeline:

1. **Lexicon Builder**
   - Maps words → unique IDs using hash maps

2. **Forward Index**
   - Stores word occurrences per document

3. **Inverted Index**
   - Maps words → documents for fast retrieval

4. **Barrel Partitioning**
   - Splits index into 64 parts for efficient loading

5. **Search Engine Core**
   - Handles ranking, scoring, and query execution

6. **Document Store**
   - Stores metadata for fast result display

---

## 📊 Performance

- ⏱️ < 500ms for single-word queries  
- ⏱️ < 1.5s for complex queries  
- 📄 70,000+ documents indexed  
- 📚 120,000+ vocabulary size  
- 🔢 5.4M+ indexed hits  

---

## 📸 Screenshots

> Add screenshots here (UI, search results, autocomplete)

---

## 🚀 Installation & Setup

```bash
# Clone the repo
git clone https://github.com/momin-bukhari/Search-Engine.git

# Navigate to project
cd Search-Engine

# Install dependencies
npm install

# Run backend
node server.js

# Run frontend
npm run dev
