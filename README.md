# About Me:

**3rd year CS student @ Santa Clara University · SWE @ Adorus · FDE Intern @ Countera**

📍 Fremont, CA · spoigai21@gmail.com · [Portfolio](https://www.shayanpoigai.dev/) · [LinkedIn](https://www.linkedin.com/in/shayanpoigai/)

---

## 🚀 What I'm working on now

- **Countera** — working on the backend for POS system
- **Adorus** — implementing a social metrics dashboard
- **[Swing Agent](https://github.com/spoigai21/swing-agent)** — shipped v0.2.0 to PyPI: a CLI agent that explains unusual stock moves from news published before the move, or abstains

---

## 🛠️  Tech Stack

**Languages**
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)

**Frameworks & Tools**
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Qt](https://img.shields.io/badge/Qt-41CD52?style=flat&logo=qt&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat&logo=pytest&logoColor=white)
![PyPI](https://img.shields.io/badge/PyPI-3775A9?style=flat&logo=pypi&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat&logo=stripe&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

**Cloud & Data**
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat&logo=googlecloud&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=flat&logo=googlebigquery&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat&logo=redis&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat)
![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=flat&logo=neo4j&logoColor=white)

**AI / ML**
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat&logo=langgraph&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat&logo=googlegemini&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat&logo=ollama&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-FF6F00?style=flat)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat)

**Others**
![Qiskit](https://img.shields.io/badge/Qiskit-6929C4?style=flat&logo=qiskit&logoColor=white)

---

## 📌 Featured Projects

### 📈 [Swing Agent](https://github.com/spoigai21/swing-agent) · [PyPI](https://pypi.org/project/swing-agent/)
An open-source CLI agent that detects unusual stock moves, retrieves news published **before** each move began, and explains the cause — or says "unexplained" rather than guessing. A **LangGraph** pipeline strips any citation that doesn't match a real retrieved article. Ingests 28 sources (SEC EDGAR, GDELT via **BigQuery**, RSS/IR feeds) into **PostgreSQL + pgvector**, deduplicated with MinHash and embeddings. A placebo test found **0 fabricated explanations in 38 trials**, and one combined BigQuery query cut projected scan volume ~99%. 412 tests, published via PyPI Trusted Publishing.
`Python` `LangGraph` `Gemini` `PostgreSQL` `pgvector` `BigQuery` `pytest`

### 💎 [Adorus Jewels](https://adorusjewels.com)
A full-stack jewelry e-commerce platform built and deployed end-to-end. A **Java 21 Spring Boot** backend over **PostgreSQL** on AWS, a **React + Vite** storefront served through CloudFront, **Stripe** payments, and CI/CD with GitHub Actions. ML features include visual similarity search with **CLIP** on AWS Lambda and AI virtual try-on.
`Java` `Spring Boot` `React` `PostgreSQL` `AWS` `Stripe`

### 🃏 [Kuhn Poker vs Quantum](https://github.com/spoigai21/kuhn-quantum-poker) · [Live Demo](https://kuhn-quantum-poker.vercel.app/)
A full-stack game where you play poker against an opponent whose strategy is computed by a **real quantum computer**. Built a 6-qubit variational circuit in Qiskit, wrapped in a FastAPI backend + React frontend. Ran it on **real IBM quantum hardware** — real-chip results matched simulation within ~1.7 percentage points on a 4,096-shot run.
`Qiskit` `IBM Quantum` `FastAPI` `React`

### 🍽️  [Agentic Restaurant RAG Pipeline](https://github.com/spoigai21/restaurant-rag)
A retrieval system that lets an AI agent answer natural-language questions about restaurants via semantic search. Built an **MCP server** exposing local data as tools for AI agents over JSON-RPC; tested on OpenWebUI with Ollama.
`Python` `ChromaDB` `Ollama` `MCP` `RAG`

### 🦠 [Disease Tracker](https://github.com/tatertotbot/AWS-Inrix-2025)
A FastAPI service serving real-time disease metrics and risk assessments with low-latency responses. Engineered an **AWS Bedrock** AI risk-scoring pipeline and designed DynamoDB schemas for scalable data ingestion.
`React` `FastAPI` `AWS Bedrock` `DynamoDB`

### 🌐 [Social Network (C++ / Qt)](https://github.com/spoigai21/socialnetwork)
A desktop social app in C++ with a Qt GUI and MVC architecture. Modeled friendships with a custom graph and generated friend suggestions via BFS traversal, with file I/O for persistence.
`C++` `Qt` `Graphs` `MVC`

### 🔔 [Internship Monitor](https://github.com/spoigai21/internship-monitor)
A Python daemon that polls 20+ company career pages and alerts me the moment a relevant internship goes live. Parses Greenhouse, Ashby, Lever, and Uber job APIs, scores each listing against a YAML profile, and routes alerts by tier — push + email for standard matches, SMS + phone call for high-priority ones. Handles the messy parts: content-based dedup so re-listed roles don't spam, stale-backfill filtering, per-domain rate limiting, and SQLite state on a persistent volume so nothing is missed across redeploys. Runs 24/7 on Railway.
`Python` `SQLite` `Twilio` `ntfy` `Railway` `Click` `pytest`

### 🧠 [Evermind](https://github.com/MihirGajjar27/prod-empathic-ai-backend)
A voice-first empathetic AI companion that listens, remembers, and responds with emotional awareness. Speech streams over WebSockets to Hume AI for real-time emotional-tone detection, and Gemini generates warm, context-aware replies. A **Neo4j knowledge graph** stores emotions and topics as nodes with their relationships as edges, giving the agent short-term memory that persists across a session instead of resetting each turn. The Next.js frontend features a React Three Fiber voice orb that reacts to live audio, a running transcript, and a real-time view of the growing knowledge graph.
`Next.js` `WebSockets` `Hume AI` `Gemini` `Neo4j` `React Three Fiber`

---

## 🏆 Highlights

- 📦 **Published `swing-agent` to PyPI** — open-source (MIT), [pypi.org/project/swing-agent](https://pypi.org/project/swing-agent/)
- 💎 **Co-Founder of Adorus** — [About Us](https://adorusjewels.com/about-us)
- 📄 **Peer-reviewed paper accepted** at HIBIBI 2026 (collocated with IEEE/ACM ASONAM), publishing with **Springer** — primary writer
- 🎓 **4.0 Major GPA** in Computer Science @ Santa Clara University
- 👨‍**CS Teaching Assistant** — mentored 40+ students in C++ and algorithms

---
