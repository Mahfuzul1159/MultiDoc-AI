# MultiDoc AI

![Python](https://img.shields.io/badge/Python-3.13-blue)
![Streamlit](https://img.shields.io/badge/Streamlit-1.49.1-orange)
![LangChain](https://img.shields.io/badge/LangChain-0.3.27-green)
![FAISS](https://img.shields.io/badge/FAISS-1.12.0-red)

**MultiDoc AI** is a Streamlit web application that allows you to **chat with multiple PDF files**. Upload your PDFs, process them, and ask questions—powered by **Google Gemini AI** through LangChain.  

The app uses **FAISS** for vector embeddings to retrieve relevant context from your PDFs for accurate and context-aware answers.

---

## Live Demo

Access the app online: [MultiDoc AI on Streamlit](https://multidoc-ai.streamlit.app/)

---

## Features

- Upload **multiple PDF files** at once
- Automatically **extract text** from PDFs
- **Split text into chunks** for better context handling
- Generate **vector embeddings** using Google Generative AI
- Query PDFs with **AI-powered conversational Q&A**
- Simple, clean **Streamlit interface**
- Developer credit in sidebar  

---

## Technologies Used

- **Python 3.13**
- **Streamlit** – Web app interface
- **LangChain** – Conversational AI
- **Google Generative AI** – Embeddings and chat
- **FAISS** – Vector database for semantic search
- **PyPDF2** – PDF text extraction
- **python-dotenv** – Load API keys from `.env`

---

## Getting Started (Local)

1. **Create a virtual environment
-python -m venv venv
-source venv/bin/activate   # Linux/macOS
-venv\Scripts\activate      # Windows

2. Install dependencies
-pip install -r requirements.txt

3.Add API key
-Create a .env file in the root directory:
-GOOGLE_API_KEY=your_google_api_key

4.Run the app
-streamlit run bot.py








