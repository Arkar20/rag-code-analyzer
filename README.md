# 🧠 CodeBase Analyzer

**CodeBase Analyzer** is an AI-powered developer tool that lets you upload and chat with your codebase. It uses RAG (Retrieval-Augmented Generation) to answer questions like “What does this project do?” or “Where is the database connection initialized?” You can interact with your code through a chatbot UI built with Gradio, and visualize code embeddings using t-SNE and Plotly.

---

## 🔍 Key Features

- 📁 Upload and analyze any codebase
- 🤖 Ask natural language questions about your code
- ⚡ Brute-force RAG implementation for simplicity and performance
- 🧠 GPT-4o-mini by OpenAI for low-cost but accurate answers
- 🔎 Free alternative using HuggingFace sentence transformers
- 📊 Visualize code vectors in 2D/3D using t-SNE and Plotly
- 🧱 Chunking with overlap to preserve context
- 🧪 Gradio UI for easy testing and interaction

---

## 🧰 Tech Stack

| Technology        | Purpose                                 |
|------------------|-----------------------------------------|
| **LangChain**     | RAG pipeline and LLM orchestration      |
| **Chroma**        | Vector database for storing embeddings  |
| **OpenAI GPT-4o-mini** | LLM for answering code questions    |
| **SentenceTransformers** | Free embeddings alternative       |
| **Plotly + t-SNE**| Embedding visualization                |
| **Gradio**        | Chat UI                                 |
| **dotenv**        | Manage API keys securely                |

---

## 🗂️ Project Structure

  - code/: "Place your codebase folders here"
  - main.py: "Main execution file"
  - utils.py: "Utility functions for processing"
  - rag_pipeline.py: "Core RAG logic"
  - visualize.py: "Vector visualization with t-SNE + Plotly"
  - .env: "OpenAI API key (not committed)"
  - README.md: "Project documentation"


## 🛠️ Requirements

- Python 3
- OpenAI API Key 


## 🔧 Setup Instructions

```

```
## Installation

Clone the repository

```bash
  git clone https://github.com/your-username/codebase-analyzer.git
  cd codebase-analyzer
```
    
Create Virtual env

```bash
python3 -m venv .venv
source .venv/bin/activate
```

Activate Virtual Environment

```bash
pip install -r requirements.txt
```

Add .env variable
```bash
OPENAI_API_KEY=your_openai_key_here
```

Run nb File
## Roadmap

- Develop Api endpoint

- use pgsql to store embedding

- Deploy to Modal

