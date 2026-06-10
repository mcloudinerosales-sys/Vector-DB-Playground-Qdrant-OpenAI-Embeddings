#  Vector DB Playground: Qdrant & OpenAI Embeddings

A technical sandbox repository dedicated to researching, experimenting, and learning vector database mechanics, geometric space distances, and AI semantic searches. This project demonstrates local indexing using **Qdrant Client** combined with data vectorization via **OpenAI's Embeddings API**.

---

##  Tech Stack & Architecture

* **Language:** Python (>=3.14 recommended / v3.11+ compatible)
* **Vector Database:** Qdrant (Local disk storage system under `./vector-store`)
* **AI Model Engine:** OpenAI API (`text-embedding-3-small`)
* **Environment Manager:** Python Virtual Environment (`venv`) & `python-dotenv`

---

##  Step-by-Step Setup & Execution Guide

Follow these sequential steps to establish your environment variables and execute the semantic search scripts:

### Step 1: Environment Initialization
Clone the repository, open your terminal inside the root directory, and provision a localized environment runner:
```bash
# Create the virtual environment
python -m venv .venv

# Activate the workspace runner (Windows - Git Bash)
source .venv/Scripts/activate

# Activate the workspace runner (Mac / Linux)
source .venv/bin/activate

```

### Step 2: Install Package Dependencies

Install the required AI and database integration drivers pinned inside the system specifications:

```bash
pip install qdrant-client openai python-dotenv

```

### Step 3: Configure Authentication Tokens

Create an environment security layer file named **`.env`** in the root workspace tree and insert your live authorization token:

```text
OPENAI_API_KEY=your_actual_openai_api_key_here

```

### Step 4: Execute Playground Scripts

#### Script A: Run Mathematical Mock Vectors (No API Key Required)

Tests local database operations, structural index queries, and coordinate processing mechanics:

```bash
python qdrant_with_simple_data.py

```

#### Script B: Run Semantic AI Search (OpenAI Key Required)

Transforms raw programming language strings into 1536-dimensional semantic vector vectors, performs chunk bulk upserts, and triggers high-performance payload context filters:

```bash
python qdrant_with_embedding_data.py

```
