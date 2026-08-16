<div align="center">
<img src="https://github.com/Silwal103.png" width="150" style="border-radius: 50%;" alt="Arjun Silwal"/>

# Hi, I'm Arjun Singh Silwal 👋

### Building AI-integrated backend systems — currently focused on SDE & GenAI Engineering roles

📍 Mumbai, India &nbsp;|&nbsp; 🎓 B.E. Information Technology, VESIT (2026) &nbsp;|&nbsp; CGPA 8.61

[![Open to Work](https://img.shields.io/badge/Open%20to%20Work-brightgreen?style=flat&logo=briefcase&logoColor=white)](https://www.linkedin.com/in/arjun-silwal-a1a3a5309/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/arjun-silwal-a1a3a5309/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:singharjun222005@gmail.com)

</div>

---

## About Me

- 🔧 I build full-stack systems with a retrieval/AI layer bolted on where it actually solves a problem 
- 🧠 Most recent focus: RAG pipelines (chunking strategy, embedding retrieval, LLM inference serving) and where they break in practice
- 🏫 Final-year IT undergrad at VESIT, Mumbai — shipped two production-adjacent projects during coursework, not just class assignments
- 🧪 Comfortable in Java/Spring Boot on the backend, Next.js on the frontend, and Python for anything ML/pipeline-shaped
- 📚 Currently sharpening DSA (Java) and going deeper on distributed systems fundamentals

---

## Tech Stack

**Languages**
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)

**Backend**
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)

**Frontend**
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white)

**Databases & Infra**
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white)

**AI / ML**
![Gemini](https://img.shields.io/badge/Gemini_2.5-8E75B2?style=flat&logo=googlegemini&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat&logo=meta&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat&logo=ollama&logoColor=white)

---

## Featured Projects

### 🖨️ [PrintDrop](https://github.com/Silwal103/PrintDrop)
A privacy-first print lab queue system for college print stations — built because the existing setup exposed everyone's files to whoever was standing at the counter.
- **Stack:** Next.js, Supabase, Vercel
- **What's interesting:** Access control runs entirely at the application layer using high-entropy, single-use codes with a 2-hour TTL — no session state, no exposed file listing. Actually used daily by classmates, not a shelved demo.

### 📄 Placement Intelligence Platform
A RAG-based Q&A system over placement documents, built to cut through the noise of scattered PDFs during placement season.
- **Stack:** Next.js frontend, FastAPI inference service, Spring Boot caching layer, PyMuPDF → semantic chunking → FAISS retrieval → Gemini 2.5 Flash generation
- **What's interesting:** The retrieval quality problem — chunking strategy and embedding relevance mattered more to output quality than which LLM sat at the end of the pipeline. Spring Boot layer added purely for response caching, not as a service-oriented rewrite.

### 📲 WhatsApp Notification Router — HackerRank Orchestrate
An offline-first multimodal pipeline that parses WhatsApp exports and routes actionable messages, without relying on any cloud API.
- **Stack:** EasyOCR, faster-whisper, FAISS, Ollama (fully local inference)
- **What's interesting:** Everything runs offline — OCR, speech-to-text, and generation are all local models. Achieved 83% action-classification accuracy on the test set.

### ⚖️ KanunAI — AI-Powered Virtual Legal Assistant
A RAG-based legal assistant that helps non-experts understand contracts and case judgments through summarization, clause risk-flagging, and precedent search — built as a 4-person team project, later written up as a research paper.
- **Stack:** Next.js 15 (App Router), React 19, Socket.io, Redux Toolkit — my scope was the frontend plus two of the retrieval-backed features
- **My contribution:**
  - Built the Next.js frontend, including the document upload flow and the real-time chat interface (WebSocket-based streaming for LLM responses)
  - Built the **timeline extraction** feature — parses case documents into chronological event sequences using date detection and LLM validation
  - Built the **precedent search** feature — embedding-based retrieval that surfaces similar past cases with citation, court, and similarity reasoning, rather than plain keyword matching
- **What's interesting:** Precedent search doesn't just keyword-match — it retrieves on semantic similarity via FAISS and has the LLM explain *why* a case is relevant, which is a meaningfully different problem from summarization (explaining a relationship between two documents vs. condensing one).

---

## Achievements

- 🏆 Finalist, Nomura KakushIN 9 Hackathon 

---

## Currently Exploring

- Backend scalability patterns
- Deepening Java/Spring Boot for backend-heavy interview loops
- DSA in Java — steadily working through gaps in DP and recursion

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/arjun-silwal-a1a3a5309/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:singharjun222005@gmail.com)

</div>
