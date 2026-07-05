# 📄 PDF Query Assistant with LangChain

An AI-powered application that lets you ask questions about PDF documents using **LangChain**, **OpenAI**, and **FAISS**. The project extracts text from PDFs, creates vector embeddings, and retrieves the most relevant information to answer natural language queries.

---

## 📖 Overview

Reading lengthy PDF documents can be time-consuming. This project simplifies document analysis by allowing users to interact with PDFs through a question-answering interface.

Using Retrieval-Augmented Generation (RAG), the application searches the document for relevant content before generating accurate responses based on the PDF.

---

## ✨ Features

- 📂 Load and process PDF documents
- 📑 Extract text from PDF files
- ✂️ Split large documents into manageable chunks
- 🧠 Generate vector embeddings using OpenAI
- 🔍 Perform semantic search with FAISS
- 💬 Ask questions in natural language
- ⚡ Retrieve accurate answers from document content
- 🌐 Supports both local and online PDF files

---

## 🛠️ Tech Stack

- Python
- LangChain
- OpenAI API
- PyPDF2
- FAISS
- Tiktoken

---

## 📁 Project Structure

```
PDF-Query-LangChain/
│
├── PdfQueryLangchain.ipynb
├── budget_speech.pdf
├── requirements.txt
└── README.md
```

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/pdf-query-langchain.git
cd pdf-query-langchain
```

Install the required libraries:

```bash
pip install langchain
pip install openai
pip install PyPDF2
pip install faiss-cpu
pip install tiktoken
```

---

## 🔑 API Configuration

Before running the notebook, add your OpenAI API key:

```python
import os

os.environ["OPENAI_API_KEY"] = "YOUR_OPENAI_API_KEY"
```

---

## ▶️ Usage

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Install the required dependencies.
3. Add your OpenAI API key.
4. Load a PDF document.
5. Extract and split the document into text chunks.
6. Generate embeddings and store them in a FAISS vector database.
7. Ask questions about the document in natural language.
8. Receive AI-generated answers based on the document content.

---

## 🔄 Workflow

```
PDF Document
      │
      ▼
Extract Text (PyPDF2)
      │
      ▼
Text Chunking
      │
      ▼
OpenAI Embeddings
      │
      ▼
FAISS Vector Store
      │
      ▼
Semantic Search
      │
      ▼
LangChain QA Chain
      │
      ▼
Answer to User Query
```

---

## 💡 Example Queries

- What is the vision for Amrit Kaal?
- What are the key objectives of the budget?
- Summarize the main points of the document.
- What are the proposed agriculture initiatives?
- Explain a specific section of the PDF.

---

## 📚 Applications

- Research paper analysis
- Financial report exploration
- Legal document search
- Government policy documents
- Academic study materials
- Business reports
- Technical documentation
- Enterprise knowledge retrieval

---

## 🔮 Future Improvements

- Support multiple PDF documents
- Streamlit-based web interface
- Chat history and conversational memory
- Source citations with page numbers
- OCR support for scanned PDFs
- Multi-language document querying
- Integration with cloud storage services

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository, improve the project, and submit a pull request.

---

## 📄 License

This project is licensed under the MIT License and is intended for educational and learning purposes.

---

## 👨‍💻 Author

Developed as a Retrieval-Augmented Generation (RAG) project using LangChain, OpenAI, and FAISS for intelligent PDF question answering.
