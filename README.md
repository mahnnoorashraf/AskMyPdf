# AskMyPdf 💬

AskMyPdf is a Python + Streamlit application that lets you upload a PDF and ask questions about it using natural language.  
It uses OpenAI embeddings + LangChain’s FAISS vector store to find the most relevant chunks of text, and then uses a Large Language Model (LLM) to generate accurate answers.

---

## ✨ Features

- 📄 **Upload Any PDF** – Reads and extracts text from your file.
- 🔍 **Smart Chunking** – Splits your PDF into overlapping text chunks for better context.
- 🧠 **Semantic Search** – Uses OpenAI embeddings + FAISS for fast similarity search.
- 💬 **LLM-Powered QA** – Streams answers to your questions directly in the app.
- 📊 **Token Usage Report** – Shows how many tokens your query consumed (for cost tracking).

---

## 🛠️ Tech Stack

- **Python** 3.10+
- **LangChain** 0.0.154
- **OpenAI API** (with `openai==0.27.8` for compatibility)
- **FAISS CPU** 1.8.0
- **PyPDF2** 3.0.1
- **Streamlit** 1.18.1

---

## 🚀 Installation

Clone this repository and install dependencies in a virtual environment:

```bash
git clone https://github.com/mahnnoorashraf/AskMyPdf.git
cd AskMyPdf

python3 -m venv venv
source venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
 `.env` file:

---



