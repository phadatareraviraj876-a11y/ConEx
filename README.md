# ConEx
Concept Explainer Agent
# Agentic RAG Streamlit Application — Multi-Document Concept Explainer
# linit access


📚 Purpose

This application provides a **research-assistant-style platform** where users can:

- Upload or link multiple **PDF research papers**
- Automatically **index** them into an **in-memory FAISS vector store**
- Ask **concept-level questions**
- Retrieve and summarize relevant context using **LangChain + OpenAI embeddings**
- Get a coherent, **Agentic AI explanation** synthesized via **CrewAI agents**



🧩 Key Features

- ✅ Upload multiple PDFs (up to 5)
- ✅ Index via OpenAI embeddings (FAISS vector store)
- ✅ Multi-document RAG retrieval
- ✅ CrewAI-based retriever + summarizer agents
- ✅ Streamlit UI with real-time interaction
- ✅ Session caching and reruns for seamless UX
- ✅ In-memory, privacy-preserving local processing

## 🚀 Core Functionality Overview

<aside>
1. Streamlit Frontend

The app runs an interactive **Streamlit interface** with two main sections:

- **Left Panel:** Handles initialization, OpenAI API setup, and PDF uploads (or URL-based downloads)
- **Right Panel:** Enables the user to chat with the uploaded papers and explore scientific concepts

All application states (API key, docs, embeddings, chat history) are stored in **Streamlit's session state** for persistence during runtime.

</aside>
