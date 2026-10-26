# ⚡ Smart AI Router & Semantic Vector Cache

An intelligent, lightweight API routing service built with **FastAPI**, **SentenceTransformers**, and **SQLite**. 

This project significantly reduces LLM API costs and response latency by using semantic vector search to serve instantly cached responses for contextually similar user queries.

---

## ✨ Key Features

* 🚀 **Semantic Caching**: Uses `all-MiniLM-L6-v2` embeddings to calculate cosine similarity between incoming prompts and previously stored responses.
* ⚡ **Ultra-Low Latency**: Delivers cached responses in milliseconds, avoiding unnecessary external LLM calls.
* 💰 **Cost Efficiency**: Reduces token usage and API costs for repetitive or semantically close queries.
* 📊 **Transparent Metadata**: Returns clear cache source details (`source: "cache"` vs `source: "generated_and_cached"`) along with similarity scores.
* 🛠️ **RESTful API**: Clean async endpoints documented with Swagger UI.

---

## 🏗️ Tech Stack

* **Language**: Python 3.10+
* **Framework**: FastAPI + Uvicorn
* **ML / Vector Embeddings**: SentenceTransformers (`all-MiniLM-L6-v2`)
* **Database**: SQLite (Vector & Metadata Storage)

---

## ⚡ Quickstart

### 1. Clone the Repository
```bash
git clone [https://github.com/NelliTen/smart-ai-router.git](https://github.com/NelliTen/smart-ai-router.git)
cd smart-ai-router
FastAPI-based Intelligent Router &amp; Semantic Vector Cache using SentenceTransformers
