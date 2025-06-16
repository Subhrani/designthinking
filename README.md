# AI-Based Automated Question Paper Generator

An intelligent and user-friendly system designed to automatically generate syllabus-aligned question papers using Groq-hosted Large Language Models (LLMs), HuggingFace Transformers, FAISS vector search, and Streamlit.

### Features
- Upload and parse syllabus PDFs
- Extract content and segment into chapters or units
- Generate questions across Bloom’s Taxonomy levels (Remember, Understand, Apply)
- Semantic vector embeddings using Hugging Face + FAISS
- Dynamic question generation using Groq LLM via LangChain
- Export question papers as editable Word (.docx) documents
- Streamlit-based frontend + FastAPI backend

###  Tech Stack
-  Groq-hosted LLM (LLaMA-3)
-  Hugging Face Transformers (`all-MiniLM-L6-v2`)
-  FAISS vector store
-  PDF parsing (PyMuPDF, pdfplumber)
-  Backend: FastAPI
-  Frontend: Streamlit
-  Deployment: Local (venv)

### Why this project?
Manual question paper creation is slow and error-prone. Our AI system reduces the time from 2–3 hours to just 3–5 minutes — while improving syllabus relevance, diversity in cognitive levels, and export readiness.
