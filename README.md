<div align="center">

# Hi, I'm Aditya Sarade ✨

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=22&pause=1000&color=58A6FF&center=true&vCenter=true&random=false&width=620&lines=AI+Engineer+%E2%80%A2+Building+Production+AI+at+Medikabazaar;Multi-Agent+Systems+%26+RAG+Architect;FastAPI+%2B+LangGraph+%2B+Vector+Search;Python+Package+Publisher+(Asterix%2C+QMem+on+PyPI);Shipping+AI+from+prototype+%E2%86%92+production" alt="Typing SVG" /></a>

<br/>
<p>
<a href="https://www.linkedin.com/in/adityasarade/" target="_blank">
<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="mailto:aditya.sarade2003@gmail.com">
<img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
<a href="https://github.com/adityasarade">
<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"/>
</a>
<a href="https://pypi.org/user/adityasarade/">
<img src="https://img.shields.io/badge/PyPI-3775A9?style=for-the-badge&logo=pypi&logoColor=white"/>
</a>
</p>

</div>

---

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=adityasarade&theme=nord&hide_border=true&area=true" alt="Contribution Graph"/>
</div>

## About Me

AI Engineer focused on taking systems from prototype to production. I architect multi-agent orchestration pipelines, low-latency FastAPI services, and vector-search workflows that ship to real users — not stay in notebooks. Currently building the foundational AI stack at **Medikabazaar** under the EVP of Technology.

- **Agentic AI:** robust memory layers, multi-agent orchestration with LangGraph, tool-driven autonomy.
- **Retrieval at Scale:** Qdrant / Pinecone / FAISS / ChromaDB pipelines tuned for latency and cost.
- **Production Engineering:** FastAPI + async + queues (TaskIQ / Celery / RabbitMQ) on AWS & Vertex AI.
- **Published Packages:** [Asterix](https://pypi.org/project/asterix-ai/) and QMem on PyPI.

---

## Work Experience

### AI Engineer Intern · Medikabazaar
*(February 2026 – Present)* &nbsp;·&nbsp; Reporting to the Executive VP of Technology &nbsp;·&nbsp; Founding member of the AI initiative

- Shipped the **Image Enhancement Platform** (flagship): FastAPI service deployed on **AWS (Vertex AI, S3, Kafka, EC2, Jenkins CI)** — **~14,000 product images live** on the marketplace, all converted to WebP for measurable SEO + page-load wins
- Built the **SEO Blog Agent** end-to-end: **~10.4K LOC** Python pipeline ingesting **21K Ahrefs keywords** against 999 SKUs, clustering them into 624 product groups, plus a **~7K LOC React/TypeScript** dashboard, automated three-size banner generator, and CMS publishing — **10+ blogs already live** with zero engineering involvement per release
- Architected the **AI Command Centre**, a 6-layer hybrid multi-agent platform (orchestrator + 5 shared functional agents + per-product liaisons) for company-wide observability, evaluation, cost tracking, and guardrails — projected **40–60% reduction** in org-wide LLM spend
- Delivered audits across **27 codebases + JIRA** (now a recurring monthly responsibility) and **~₹3L+** in direct cost savings via Gemini Batch API, async pipelines, cache-hit optimisation, and a JSpreadsheet → community-edition migration
- Drove **AI enablement** across the org: onboarded engineers and non-technical teams on Claude / Claude Code / Antigravity / Amazon Q; integrated Google Ads, Analytics, and Search Console with Claude Code via MCP

**Stack:** `Python` `FastAPI` `AWS` `Vertex AI` `Kafka` `S3` `EC2` `Jenkins` `Gemini API` `React` `TypeScript` `Playwright` `Firecrawl`

---

### AI Engineer Intern · Wasserstoff Innovations
*(June 2025 – October 2025)*

- Built **FastAPI backend** integrating Google Gemini API and OpenAI embeddings for legal document analysis, semantic search, and text-to-SQL generation on DuckDB
- Designed **vector embedding workflows** with Qdrant and Redis caching, reducing query latency by **~90%**
- Developed **multi-agent HR automation system** using LangGraph and MongoDB for candidate evaluation and behavioral analysis
- Implemented async data pipelines with **TaskIQ/Celery** and **RabbitMQ** for background assessment generation
- Created **QMem**, a Python CLI library for vector search automation (published on PyPI)

**Stack:** `Python` `FastAPI` `LangGraph` `Qdrant` `MongoDB` `Redis` `RabbitMQ` `Gemini API` `DuckDB`

---

### Data Science Intern · AdGama Digital
*(February 2025 – April 2025)*

- Developed and fine-tuned **15+ ML/DL models** (XGBoost, CNNs, Neural Networks) for classification and regression tasks on **100K+ row datasets**
- Created **reusable preprocessing pipelines** from scratch across tabular, time-series, and image/text data
- Deployed **10+ trained models** into production using Streamlit, Gradio, FastAPI, and Django

**Stack:** `Python` `TensorFlow` `XGBoost` `Streamlit` `FastAPI` `Django` `Pandas` `NumPy`

---

## Featured Projects

### 1. [Asterix](https://github.com/adityasarade/Asterix) — Agent Memory Framework
> *Python library for stateful AI agents with editable memory blocks and semantic retrieval. **Published on PyPI.***
- **Core Tech:** Python, Qdrant Cloud, SQLite, decorator-driven tool registration
- **Why it matters:** Lets agents persist context across sessions and retrieve memory semantically — the missing piece for production-grade autonomous systems

---

### 2. [OSCAR](https://github.com/adityasarade/OSCAR) — GitHub-Specialized AI Coding Assistant
> *VS Code extension + CLI powered by my own Asterix framework and **Gemini 2.5 Flash via Vertex AI**, specialized for git workflows — branch comparison, PR review, diff analysis, and safe automation.*
- **Core Tech:** Python, FastAPI (SSE streaming), TypeScript VS Code extension, Asterix (ReAct loop + memory), Vertex AI, Playwright, Tavily
- **What's inside:** 15 registered tools (9 git · shell · web search · browser), 12 HTTP endpoints, 4-tier risk model with human-in-the-loop confirmations, typed `CONFIRM` for dangerous ops, rotating JSONL audit log
- **Why it matters:** Real demonstration of agentic orchestration with production safety: ~2.3K backend LOC, 15 tests, CI across Python 3.10/3.11/3.12, ~9 months of iteration

---

### 3. [QueryPilot](https://github.com/adityasarade/Query-Pilot) — RAG-Based SQL Copilot
> *Real-time SQL autocompletion inside MySQL Workbench & PostgreSQL with **95%+ acceptance rate** across 20+ sessions.*
- **Core Tech:** LLaMA 3 via Groq, Pinecone, MLflow, Docker, YAML-driven configs
- **Impact:** Latency cut by **50%+** via Dockerized deployment with preloaded models and clipboard hooks

---

### 4. [Document Researcher](https://github.com/adityasarade/Document-Researcher) — Multi-PDF Theme Synthesizer
> *Multi-PDF semantic search with OCR and cross-document theme synthesis.*
- **Core Tech:** FastAPI, FAISS, Tesseract OCR, Sentence-Transformers, Groq LLM
- **Deployed:** Hugging Face Spaces (backend) + Vercel (frontend)

---

### 5. [Agentic AI Tutor](https://github.com/adityasarade/Agentic_AI_Tutor) — Adaptive EdTech Platform
> *Intelligent tutoring system delivering personalized learning paths through multi-agent orchestration.*
- **Core Tech:** Python, LangGraph, FastAPI, ChromaDB, OpenAI, Gemini
- **Why it matters:** Democratizes access to high-quality, personalized education by adapting to each learner's pace and style

---

<div align="center">
<a href="https://github.com/adityasarade?tab=repositories">
<img src="https://img.shields.io/badge/View%20All%20Projects-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>
</div>

---

## Tech Stack

<div align="center">

### Languages & Frameworks
<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white"/>
<img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white"/>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
<img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
<img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white"/>
</p>

### AI / ML & LLMs
<p>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white"/>
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white"/>
<img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white"/>
<img src="https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white"/>
<img src="https://img.shields.io/badge/Anthropic-D97757?style=for-the-badge&logo=anthropic&logoColor=white"/>
<img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/>
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white"/>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>
<img src="https://img.shields.io/badge/MCP-0A0A0A?style=for-the-badge&logoColor=white"/>
</p>

### Vector Stores & Databases
<p>
<img src="https://img.shields.io/badge/Qdrant-24292F?style=for-the-badge&logo=qdrant&logoColor=white"/>
<img src="https://img.shields.io/badge/Pinecone-000000?style=for-the-badge&logo=pinecone&logoColor=white"/>
<img src="https://img.shields.io/badge/FAISS-0866FF?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/ChromaDB-cc2b5e?style=for-the-badge&logo=chroma&logoColor=white"/>
<img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
<img src="https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black"/>
<img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white"/>
</p>

### Cloud, DevOps & Infra
<p>
<img src="https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white"/>
<img src="https://img.shields.io/badge/Vertex%20AI-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white"/>
<img src="https://img.shields.io/badge/Google%20Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white"/>
<img src="https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white"/>
<img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white"/>
<img src="https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white"/>
<img src="https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white"/>
<img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"/>
</p>

</div>

---

## GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=adityasarade&theme=nord&hide_border=true&show_icons=true&count_private=true&include_all_commits=true" height="180" alt="GitHub Stats"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=adityasarade&theme=nord&hide_border=true&layout=compact&langs_count=8" height="180" alt="Top Languages"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=adityasarade&theme=nord&hide_border=true" alt="GitHub Streak"/>
</div>

---

<div align="center">
  <img src="https://raw.githubusercontent.com/adityasarade/adityasarade/output/snake.svg" alt="Snake animation" />
</div>

<div align="center">
  <sub>If you've come here from my resume — thanks for stopping by. Feel free to reach out via any of the channels above.</sub>
</div>
