# AI_Chatbot-using-LLM
A full-stack LLM-powered AI Chatbot built with a modern, scalable architecture:

🧠 OpenAI GPT-4o / GPT-3.5
⚡ FastAPI Backend
💻 React Frontend (Vite)
🔍 RAG (Retrieval-Augmented Generation)
🧩 Modular Multi-Agent System
🔒 Safe, Domain-Restricted Prompting
This system supports 5 intelligent domains:

🎓 Education
💻 Coding
⚕️ Medical (safe, non-prescriptive explanations)
⚖️ Legal (non-advisory explanations)
💬 General conversation

🌐 Live Deployment

👉 🚀 Open the Live AI Chatbot

🎯 Key Features

🧠 1. Domain-Aware Multi-Agent System

Every query is classified into one expert domain:

Domain	Purpose
Education	Theory, explanations, step-by-step learning
Coding	Debugging, optimization, code generation
Medical	Safe educational medical insights
Legal	Legal concepts (educational only)
General	Normal conversation & reasoning
Each domain uses a custom engineered prompt template for structured, safe, high-quality responses.

📚 2. RAG Pipeline (PDF/TXT Upload + FAISS Retrieval)

Supports:

PDF/TXT ingestion
Text extraction
Chunking
Embedding via HuggingFace SentenceTransformers (MiniLM-L6-v2)
FAISS vector indexing
Top-K semantic retrieval
⭐ Hugging Face Transformers are used for embeddings only Inference is done using OpenAI GPT models, not HF models.

💻 3. Modern React Frontend (Vite)

UI includes:

✨ Animated AI typing
🕒 Timestamps
📜 Chat history export
🎛️ Sliding sidebar
🗂️ File upload for RAG
🎨 Domain-colored chat bubbles
⬇️ Smooth auto-scroll
🔔 Toast notifications
Frontend lives in /frontend/src/.

⚡ 4. FastAPI Backend

Endpoints:

Method	Endpoint	Description
POST	/chat	Main chat interface
POST	/upload	Document ingestion (RAG)
GET	/health	Health check
WS	/stream	Streamed responses
🧩 5. Clean Modular Architecture

Includes:

Agents
Prompt templates
RAG system
Domain router
OpenAI LLM wrapper
Context manager
Everything is clean, extendable, and production-ready.

📦 Tech Stack

Frontend

React (Vite)
Axios
Tailwind (optional)
Backend

FastAPI
OpenAI GPT-4o / GPT-3.5 (primary LLM)
HuggingFace SentenceTransformers (embedding only)
FAISS CPU
PyPDF2
