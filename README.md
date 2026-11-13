<h1 align="center">Hi, I'm Chirag Duhoon 👋</h1>

<p align="center">
  <strong>AI/ML Engineer | Backend Systems | Computer Vision</strong>
</p>

<p align="center">
  Building production AI apps with <code>Python</code> & <code>React</code> | RAG • Agents • YOLO • FastAPI | Open to internships
</p>

<p align="center">
  <a href="https://chiragduhoon.github.io/portfolio/">Portfolio</a> ·
  <a href="mailto:chiragduhoon1@gmail.com">Email</a> ·
  <a href="https://www.linkedin.com/in/chirag-duhoon-790b48404/">LinkedIn</a> ·
  <a href="https://leetcode.com/u/alien07/">LeetCode</a>
</p>

---

## 🎯 About Me

I build **AI systems that reason transparently**: RAG engines that cite the exact source page, triage systems with a tested safety net, and evaluations that show the numbers. I'm a B.Tech AI student at Bennett University, working where LLMs, computer vision and real-time backends meet.

- 🧠 Agentic RAG over **363 official university documents** on a self-hosted Qwen3-14B: **31/31** on a real student-question eval (up from 72%)
- 🛡️ Fine-tuned **HingRoBERTa + TF-IDF ensembles** for Hinglish hate-speech detection: macro-F1 **0.744 → 0.806**, with a bounded local LLM agent for disguised slurs
- 🩺 AI triage in English, Hindi and Hinglish whose red-flag net catches **26/26 emergencies** on a labelled test set
- 👁️ YOLO11 detector for 17 Indian dishes: **mAP@0.5 = 0.80**, 124 ms per image on a laptop CPU

---

## 🛠️ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

**Backend & AI/ML**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=for-the-badge&logo=websocket&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma·PostgreSQL-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO·Computer_Vision-111F68?style=for-the-badge)
![LangGraph](https://img.shields.io/badge/LangGraph·Agents-1C3C3C?style=for-the-badge)
![Qdrant](https://img.shields.io/badge/Qdrant·Vector_Search-DC244C?style=for-the-badge)
![Ollama](https://img.shields.io/badge/Ollama·Self--hosted_LLMs-000000?style=for-the-badge)
![LLMs](https://img.shields.io/badge/LLM_Pipelines-8A2BE2?style=for-the-badge)
![RAG](https://img.shields.io/badge/RAG·ChromaDB-FF6B35?style=for-the-badge)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

**DevOps & Tools**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## 🚀 Featured Projects

| Project | Description | Tech Stack | Links |
|---------|-------------|-----------|-------|
| **BENNETT ONE** | University assistant over 363 official documents: agentic RAG that cites the page, a tested rule engine (not the LLM) decides eligibility, every claim verified against its source. **31/31** on a real student-question eval | LangGraph, Qwen3-14B (self-hosted), Qdrant, PostgreSQL, FastAPI, React | [GitHub](https://github.com/chiragduhoon/bennett-one) |
| **HinglishGuard** | Hindi/Hinglish abuse and religious-hate moderation: fine-tuned transformer ensembles plus a local tool-calling agent that decodes disguised slurs ("ch*tiya") and reads context. HOT macro-F1 **0.806**, human-review load on THAR cut from 85% to 57% | HingRoBERTa, XLM-R, PyTorch, Ollama, Streamlit | [GitHub](https://github.com/chiragduhoon/hinglishguard) |
| **Sanjeevani — AI Healthcare Triage** | Replaces verbal ER intake with structured AI triage: voice/text symptoms in English, Hindi or Hinglish → risk level → live doctor dashboard. Deterministic red-flag net catches **26/26** emergencies | Python, FastAPI, LLMs, WebSockets, React | [GitHub](https://github.com/chiragduhoon/sanjeevani-ai-triage) · [Live Demo](https://sanjeevani-frontend-zaah.onrender.com/) |
| **Chitragupt — Brand Memory Engine** | Hallucination-resistant brand Q&A: dual-collection RAG with guaranteed rule recall, self-critique loop and a transparent trust score | LLMs, ChromaDB, FastAPI, Groq | [GitHub](https://github.com/chiragduhoon/brand-memory-engine) |
| **StockLens** | Nifty 50 research workspace on real data: 1-year prices, reported financials (USD reporters converted, stale statements flagged), analyst consensus, and news scored by **FinBERT**, explained by a self-hosted LLM that must cite evidence records | FastAPI, React, Qwen2.5 (Ollama), FinBERT, yfinance | [GitHub](https://github.com/chiragduhoon/stocklens) |
| **NutriScan** | Detects 17 Indian dishes in a photo and estimates the meal's calories. **mAP@0.5 = 0.80**, runs on a laptop CPU in 124 ms | Python, YOLO11, PyTorch, Streamlit | [GitHub](https://github.com/chiragduhoon/nutriscan) |
| **BURank** | LeetCode leaderboard platform for universities: live stats, batch-vs-batch rankings, daily challenges with First Blood mechanics | Next.js, TypeScript, Prisma, PostgreSQL | [GitHub](https://github.com/chiragduhoon/BURank) · [Live Demo](https://bu-rank-three.vercel.app/) |
| **Dhobi Clinic** | Campus laundry platform: QR-tracked bags, row-locked one-stage-per-scan workflow, OTP collection; student/worker app + admin dashboard | Node.js, PostgreSQL, Flutter, React | [GitHub](https://github.com/chiragduhoon/dhobi-clinic) |
| **Leet2Git** | Chrome extension that auto-commits every accepted LeetCode solution to GitHub with real-time tracking | JavaScript, Chrome APIs, GitHub API | [GitHub](https://github.com/chiragduhoon/leet-2-git) |

---

## 📊 GitHub Activity

<p align="center">
  <img src="https://streak-stats.demolab.com?user=chiragduhoon&theme=tokyonight&hide_border=true" alt="GitHub streak" />
</p>

<p align="center">
  <img src="assets/f1-lights-out.gif" alt="F1-style start: five red lights, lights out, a car launches" width="100%" />
</p>

---

## 💡 What I'm Learning

- Production ML deployment at scale
- Optimizing LLM inference pipelines
- Real-time computer vision systems
- Advanced system design patterns

---

## 🔗 Let's Connect

<p align="center">
  <a href="mailto:chiragduhoon1@gmail.com">📧 Email</a> •
  <a href="https://www.linkedin.com/in/chirag-duhoon-790b48404/">🔗 LinkedIn</a> •
  <a href="https://leetcode.com/u/alien07/">💻 LeetCode</a> •
  <a href="https://github.com/chiragduhoon">🐙 GitHub</a>
</p>

<p align="center">
  <i>Building systems that don't just work: they explain themselves. Open to internships & collaborations! 🚀</i>
</p>
