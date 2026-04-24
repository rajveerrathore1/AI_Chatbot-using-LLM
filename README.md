# 🚀 AI Chatbot using LLMs
Multi-Domain Intelligent Assistant
A full-stack LLM-powered AI chatbot built with a modern, scalable architecture.


# 🌐 Live Deployment
👉 🚀 Open the Live AI Chatbot(https://ai-chatbot-using-ll-ms.vercel.app/)


# 🧠 Core Stack 
🧠 OpenAI GPT-4o / GPT-3.5  
⚡ FastAPI Backend  
💻 React Frontend (Vite)  
🔍 RAG (Retrieval-Augmented Generation)  
🧩 Modular Multi-Agent System  
🔒 Safe, Domain-Restricted Prompting  


# 🌍 Supported Domains
Your chatbot intelligently handles 5 specialized domains:

| 🎯 Domain    | 📌 Purpose                                  |
| ------------ | ------------------------------------------- |
| 🎓 Education | Theory, explanations, step-by-step learning |
| 💻 Coding    | Debugging, optimization, code generation    |
| ⚕️ Medical   | Safe, non-prescriptive explanations         |
| ⚖️ Legal     | Educational legal concepts (non-advisory)   |
| 💬 General   | Everyday conversation & reasoning           |


# 🎯 Key Features

## 🧠 1. Domain-Aware Multi-Agent System
Every user query is automatically classified and routed to a domain expert.
Custom prompt templates per domain
Structured and safe responses
Context-aware reasoning
## 📚 2. RAG Pipeline (Document Intelligence)
Supports:
📄 PDF / TXT ingestion
✂️ Smart text chunking
🧠 Embeddings via SentenceTransformers (MiniLM-L6-v2)
⚡ FAISS vector search
🔍 Top-K semantic retrieval
⭐ Hugging Face is used only for embeddings — inference runs on OpenAI models.
## 💻 3. Modern React Frontend (Vite)
A smooth and interactive UI experience:
✨ Animated AI typing
🕒 Message timestamps
📜 Chat history export
🎛️ Sliding sidebar
🗂️ File upload for RAG
🎨 Domain-colored responses
⬇️ Auto-scroll
🔔 Toast notifications
📁 Located in: /frontend/src/
## ⚡ 4. FastAPI Backend
Clean and efficient API design:

| Method | Endpoint  | Description              |
| ------ | --------- | ------------------------ |
| POST   | `/chat`   | Main chat interface      |
| POST   | `/upload` | Document ingestion (RAG) |
| GET    | `/health` | Health check             |
| WS     | `/stream` | Real-time streaming      |

## 🧩 5. Modular Architecture
Built for scalability and maintainability:
🤖 Agents
🧠 Prompt templates
🔍 RAG system
🎯 Domain router
🔗 OpenAI wrapper
🗂️ Context manager
✔️ Clean
✔️ Extendable
✔️ Production-ready


# 📦 Tech Stack
## 🎨 Frontend
React (Vite)
Axios
Tailwind (optional)

## ⚙️ Backend
FastAPI
OpenAI GPT-4o / GPT-3.5
HuggingFace SentenceTransformers (embeddings only)
FAISS (CPU)
PyPDF2


# 💡 What Makes It Different?
🧠 Multi-agent intelligence instead of single chatbot
🔒 Domain-restricted safe responses
📚 Built-in knowledge retrieval (RAG)
⚡ Real-time streaming + modern UI
🧩 Clean architecture for scaling
