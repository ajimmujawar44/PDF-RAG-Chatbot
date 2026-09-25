# 📚 PDF RAG Chatbot

A Retrieval-Augmented Generation (RAG) chatbot that allows users
to upload PDF documents and ask questions using natural language.

## 🚀 Features

- PDF upload
- PDF text extraction
- Text chunking
- Hugging Face embeddings
- Chroma vector database
- Semantic retrieval
- Groq LLM
- Source page display
- Gradio dashboard

## 🧠 Architecture

PDF
 ↓
PyPDFLoader
 ↓
Text Splitting
 ↓
Hugging Face Embeddings
 ↓
ChromaDB
 ↓
Retriever
 ↓
Groq LLM
 ↓
Answer + Sources

## 🛠️ Technologies

- Python
- LangChain
- Hugging Face
- ChromaDB
- Groq
- Gradio

## 📂 Project Structure

PDF-RAG-Chatbot/
├── README.md
├── requirements.txt
├── .gitignore
├── notebooks/
│   └── PDF_RAG_Chatbot.ipynb
├── data/
│   └── README.md
└── screenshots/
    └── gradio_dashboard.png

## ▶️ How to Run

Open the notebook in Google Colab.

Install the required packages.

Add your GROQ_API_KEY to Google Colab Secrets.

Upload a PDF.

Process the PDF.

Ask questions.

## 👨‍💻 Author

Ajim Mujawar