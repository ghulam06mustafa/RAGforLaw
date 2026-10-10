<div align="center">

# ⚖️ RAGforLaw

### AI-Powered Legal Research Assistant for Pakistan

**Ask legal questions. Explore source documents. Analyze case facts.**

Built with Retrieval-Augmented Generation (RAG), LangChain, LangGraph, FastAPI, and Ollama.

<br>

![Project Status](https://img.shields.io/badge/Status-In%20Development-orange?style=for-the-badge)
![Focus](https://img.shields.io/badge/Focus-Legal%20AI-243B64?style=for-the-badge)
![Repository](https://img.shields.io/badge/Repository-Frontend%20Only-6A5ACD?style=for-the-badge)

</div>

---

## 🔎 Overview

**RAGforLaw** is an AI-powered legal research project focused on helping users explore uploaded legal documents relating to Pakistan's **Protection Against Harassment of Women at the Workplace Act, 2010**.

Instead of relying only on a language model's general knowledge, the application retrieves relevant passages from available documents and uses that context to support its responses. It also includes workflows for case analysis and document assistance.

> **Important:** This is a development project. AI-generated legal content may be incomplete or inaccurate and must be checked against authoritative, up-to-date sources.

## ✨ Key Features

| Feature | What it does |
|---|---|
| **Legal Research** | Answers legal questions using passages retrieved from uploaded documents. |
| **Case Analysis** | Produces a structured assessment of supplied case facts against retrieved legal material. |
| **PDF Upload** | Accepts legal PDFs for processing and retrieval. |
| **Document Assistance** | Helps summarize documents, extract key information, and prepare draft complaints or applications from supplied PDFs. |
| **Conversational Chat** | Provides a chat interface for legal questions and follow-up discussion. |
| **User Authentication** | Includes signup and login functionality. |
| **Local LLM** | Integrates with Ollama; the default model configured in the backend is `mistral`. |

## 🧠 How It Works

```text
Legal question / PDF
        │
        ▼
Document processing and retrieval
        │
        ▼
Relevant legal passages
        │
        ▼
LLM response grounded in retrieved context
        │
        ▼
Answer and available source references
```

The aim is to make legal information easier to explore while keeping responses tied to the material available to the system.

## 🛠️ Technology Stack

<div align="center">

| Layer | Technologies |
|:--|:--|
| **Frontend** | HTML · CSS · JavaScript |
| **API / Backend** | Python · FastAPI |
| **LLM Orchestration** | LangChain · LangGraph |
| **Model Runtime** | Ollama |
| **PDF Processing** | `pypdf` |
| **Validation** | Pydantic |
| **Retrieval** | RAG pipeline and vector-store integration |

</div>

## 🖥️ Screenshots

Screenshots will be added here as the interface is prepared for the project showcase.

<!-- Add your screenshots to a screenshots/ folder, then uncomment and update:
<div align="center">
  <img src="screenshots/chat.png" alt="RAGforLaw chat interface" width="80%">
  <p><em>RAGforLaw chat interface</em></p>
</div>
-->

## 📁 Public Repository Scope

This GitHub repository is intended to showcase the **frontend only**.

The backend implementation, database logic, RAG pipeline, authentication code, private legal-document files, and environment configuration are intentionally kept out of this public repository.

**Please do not commit:**
- Backend source code
- `.env` files, credentials, API keys, or tokens
- Database files or local vector-store data
- Private, confidential, or copyrighted documents that you do not have permission to publish

The frontend's live features require a separately configured backend. A local API address such as `localhost` will work only on the computer running that backend.

## 🚀 Run the Frontend

1. Clone or download this repository.
2. Open the `frontend/` directory.
3. Open the main HTML file in a browser if the frontend supports direct-file access.
4. To use API-backed features, run your separately configured backend and ensure the frontend's API base URL points to it.

> Exact startup instructions may vary with the current frontend configuration.

## 🛡️ Legal Disclaimer

RAGforLaw is an informational research and document-assistance tool. **It is not a substitute for advice from a qualified lawyer.** Generated responses can contain errors or omit relevant legal context. Verify laws, amendments, citations, evidence, deadlines, and procedures using authoritative sources or a qualified legal professional before relying on the output. No legal outcome is guaranteed.

## 🗺️ Roadmap

- [ ] Refine the frontend experience and usability
- [ ] Add project screenshots and a demonstration
- [ ] Improve retrieval quality and source attribution
- [ ] Evaluate answer relevance and grounding
- [ ] Document secure deployment and configuration
- [ ] Expand coverage using additional verified Pakistani legal materials

## 👤 Project

**RAGforLaw — AI-Powered Legal Research Assistant for Pakistan**

This project explores how retrieval-augmented generation can support document-grounded legal research and assistance.

## 📄 License

No license has been added yet. Until a license is specified, do not assume permission to reuse, modify, or redistribute this project's code.
