<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=180&section=header&text=Hemanth%20S%20Vas&fontSize=46&fontColor=ffffff&fontAlignY=38&desc=Agentic%20AI%20%E2%80%A2%20RAG%20Systems%20%E2%80%A2%20MLOps&descAlignY=58&descSize=16&animation=fadeIn" />

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&pause=1200&color=A78BFA&center=true&vCenter=true&width=650&lines=Building+RAG+%2B+Agentic+AI+systems;LangGraph+%7C+FastAPI+%7C+ChromaDB+%7C+Celery;Open+to+full-time+AI%2FML+engineering+roles" alt="Typing SVG" />
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hemanth-s-vas-0196b9270)
[![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/HemanthSreenivas)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hemanthsrinivas18@gmail.com)

</div>

---

## About Me

- 🎓 B.E. in AI & ML — Visvesvaraya Technological University (2022–2026)
- 📍 Based in Bengaluru, India
- 🧠 Focused on LLM agents, RAG pipelines, MLOps infrastructure, and backend APIs
- 🛠️ Working stack: LangGraph, ChromaDB, FastAPI, Celery/Temporal, Redis, Docker, GitLab CI/CD
- 💼 **Open to full-time opportunities in AI/ML engineering**

---

## Experience

### PromptIQ Technologies Pvt. Ltd. — Agentic AI Intern / Product Contributor
*Aug 2025 – Aug 2026*

- Built an Airbyte CDK-based RAG data ingestion pipeline running as standalone Dockerized connectors (no Airbyte platform, no UI/server/scheduler) — Slack and Jira sources live
- Designed state-based incremental sync with Temporal for durable, resumable workflows, including mid-sync checkpointing and crash recovery
- Wrote 62 automated tests for the ingestion pipeline and tuned the retrieval layer to sub-50ms latency
- Authored core lifecycle documentation (setup guide, project status tracking) for an internal AWS-based foundation-model fine-tuning platform spanning dataset ingestion through deployment

### Simulation AI Internships — AI Engineering Intern
*Aug 2023 – Jan 2024*

- Deployed ML models across 4 production environments with Docker, cutting failures by 15% and speeding up rollbacks by 40%
- Built an Airflow ETL pipeline for 2TB+ of data, improving throughput by 15% and reducing data errors by 25%

---

## Projects

### 🔧 MLOps LLM Automation Pipeline *(personal project)*
`Python` `FastAPI` `Celery` `Redis` `ChromaDB` `sentence-transformers` `Ollama/vLLM`

An 8-stage pipeline that turns raw data (CSV, JSON, Parquet, text) into a fine-tuned, RAG-grounded LLM agent — ingest → schema detection → embedding → training-data generation → fine-tuning → deployment → evaluation → monitoring.

- 62 pytest tests, 100% pass rate, with a GitLab CI/CD pipeline (lint → test → Docker build)
- Per-agent ChromaDB isolation to prevent data leakage between agents
- Backend abstraction switches between Ollama (dev) and vLLM (GPU) with a single env var
- Graceful degradation built in: Celery unavailable → falls back to threads; Ollama down → simulation mode

### 🤖 Agentic Code Analysis System
`Python` `tree-sitter` `LangGraph` `ChromaDB` `Celery` `FastAPI`

A multi-agent system (reviewer + refactorer + tester) that parses codebases with tree-sitter AST/CST and indexes them into ChromaDB for semantic retrieval.

- 10K+ indexed code chunks with sub-50ms semantic search

---

## Tech Stack

**Languages**
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Go](https://img.shields.io/badge/Go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white)
![Java](https://img.shields.io/badge/Java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![SQL](https://img.shields.io/badge/SQL-%2307405e.svg?style=for-the-badge&logo=postgresql&logoColor=white)

**ML / AI Frameworks**
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-%23FFD21E.svg?style=for-the-badge&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)

**LLM & Agentic AI**
![LangChain](https://img.shields.io/badge/LangChain-%231C3C3C.svg?style=for-the-badge&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-%23412991.svg?style=for-the-badge&logo=openai&logoColor=white)
`LangGraph` `LlamaIndex` `CrewAI` `AutoGen` `RAG` `FAISS` `Pinecone` `ChromaDB`

**Cloud & DevOps**
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-%230072C6.svg?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white)

**Data & Backend**
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![Django](https://img.shields.io/badge/Django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-%23231F20.svg?style=for-the-badge&logo=apachekafka&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=Apache%20Airflow&logoColor=white)

**MLOps & Observability**
`MLflow` `Weights & Biases` `Prometheus` `Grafana` `pytest` `GitLab CI/CD` `Celery`

---

## GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=HemanthSreenivas&show_icons=true&theme=midnight-purple&include_all_commits=true&count_private=true&hide_border=true"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=HemanthSreenivas&layout=compact&langs_count=8&theme=midnight-purple&hide_border=true"/>

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com/?user=HemanthSreenivas&theme=midnight-purple&hide_border=true)](https://git.io/streak-stats)

</div>

---

<div align="center">

### Open to AI/ML engineering roles and interesting collaborations

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=100&section=footer"/>

</div>
