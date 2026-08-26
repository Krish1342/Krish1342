<div align="center">

![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=2E9EF7&center=true&vCenter=true&width=600&lines=AI+%26+ML+Engineer;Building+autonomous+agents;Currently+remote+at+bizAmica)

</div>

# Hey, I'm Krish 👋

AI & Data Science student (MIT WPU, Pune) and Software Intern at **bizAmica**, working fully remote since July 2026.

I like taking things people do by hand — sifting through documents, routing tickets, digging through notes — and building systems that just do it for them. That's the thread through everything below: not "AI projects" for the sake of it, but automation that removes real manual work.

Currently looking for remote roles where I can keep doing exactly that.

---

## 🔧 What I'm building right now

**StepRoute** — a research project on step-level model routing for tool-using agents, scoped specifically to SRE/incident investigation. Most routing work picks one model per task; I'm looking at routing *per step* within an agent's tool-use trajectory, using MCP tool-schema metadata as a routing signal, and building a live evaluation setup instead of relying on static replays (which don't capture how agents actually drift in production). Early-stage, still scoping — not claiming it's done.

**Second Brain — Autonomous Sync & Cross-Reference Layer** — an AI knowledge agent that started as a straightforward RAG pipeline (PDF ingestion → OCR → chunking → embeddings → semantic search with citations) and is turning into something more agentic: it auto-syncs with Google Drive, classifies incoming documents as NEW / DUPLICATE / UPDATE / CONTRADICTION against what's already indexed, and pushes a daily digest — kept out of the vector store on purpose, so it doesn't pollute retrieval. Built on Postgres + pgvector rather than a dedicated vector DB, deliberately, to keep the infra footprint small.

---

## 🧠 Skills

![My Skills](https://skillicons.dev/icons?i=python,fastapi,react,tailwind,postgres,mongodb,tensorflow,git,vercel,vscode)

**AI/ML** — classification, regression, forecasting, CNNs/ANNs (TensorFlow, Keras), NLP, embeddings, RAG pipelines, agentic systems, model evaluation

**Backend** — Python, FastAPI, Flask, Django, REST APIs & auth, database design

**Frontend** — React, Vite, Tailwind, Streamlit

**Data** — PostgreSQL (pgvector), MySQL, MongoDB, SQLite, Power BI

**Other** — Git/GitHub Actions, Postman, basic cloud/deployment (Vercel, Netlify)

---

## 🚀 Other things I've shipped

- **AutoEDA** — one-click exploratory data analysis: point it at a dataset, get visual summaries and ML-ready insights back, no manual notebook wrangling.
- **AgroTech** — full-stack platform giving farmers fertilizer and soil-health guidance from crop data, with a live analytics dashboard. [Live demo →](https://agro-tech-roan.vercel.app/dashboard)

---

## 📫 Reach me

- Email: lodhakrish11@gmail.com
- LinkedIn: [krish-lodha](https://linkedin.com/in/krish-lodha-6b2b06343)

Open to remote AI/ML and backend roles — happy to walk through the architecture on any of the above if you're curious.
