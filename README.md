# 🦜🔗 Learning LangChain

A simple, beginner-friendly repository documenting my journey of learning **LangChain**, exploring **Large Language Models (LLMs)**, and building AI applications in Python.

---

## 📌 Overview

This project tracks hands-on practice, experiments, and notes covering:
- Connecting to modern LLM APIs (Google Gemini, OpenAI)
- LangChain fundamentals (Prompts, Models, Output Parsers)
- Chains and Runnables (LCEL)
- Memory, Retrievers, and Vector Stores
- Agents, Tools, and Workflows

---



## 🛠️ Tech Stack & Dependencies

- **Language:** Python 3.13+
- **Package Manager:** [uv](https://docs.astral.sh/uv/) / pip
- **Core Libraries:**
  - `langchain`
  - `google-genai`
  - `openai`
  - `python-dotenv`
  - `ipykernel` / Jupyter

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/DarshanKudrigi/learning-langchain.git
cd learning-langchain
```

### 2. Set up the virtual environment

Using `uv` (recommended):
```bash
uv sync
```

Or using standard `venv` & `pip`:
```bash
python -m venv .venv
# On Windows:
.venv\Scripts\activate
# On Linux/macOS:
source .venv/bin/activate

pip install -e .
```

### 3. Configure API Keys

Create a `.env` file in the root directory (you can copy `.env.example`):
```env
GEMINI_API_KEY="your_gemini_api_key_here"

---

## 👤 Author

- **Darshan Kudrigi**
