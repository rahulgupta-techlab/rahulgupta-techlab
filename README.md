<h1 align="center">
  <img
    src="https://readme-typing-svg.herokuapp.com?font=Syne&size=30&duration=3000&pause=1000&color=F97316&center=true&vCenter=true&width=600&lines=Hi+I'm+Rahul+Gupta;AI+Engineer+and+Data+Scientist;Agentic+AI+%7C+RAG+%7C+LLMs;Industrial+AI+%7C+MLOps"
    alt="Hi, I'm Rahul Gupta | AI Engineer and Data Scientist | Agentic AI, RAG, LLMs | Industrial AI, MLOps"
/>
</h1>

<p align="center">
  <a href="https://www.linkedin.com/in/rahul-gupta-49508b144/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:rahulg1397rg@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <img src="https://komarev.com/ghpvc/?username=rahulgupta-techlab&style=for-the-badge&color=F97316" alt="views"/>
</p>

---

## About Me

AI Engineer and Data Scientist with full-stack development experience, a software and data engineering background, and **5+ years** building production AI, machine learning and data systems, in startups and large enterprises, in Germany and India.

- 🏭 **Bosch**: product development and solution engineering for remote device management in industrial IoT (edge to cloud), plus industrial AI: predictive maintenance, multivariate time series, computer vision, with MLOps on MLflow.
- 🤖 **FIR e.V. at RWTH Aachen**: agentic AI and RAG for decision support (LangGraph, MCP, tool calling, hybrid retrieval) with guardrails and an evaluation framework for quality, latency and cost. **+40% context relevance**; Shape process-mining platform with **80% lower API latency**.
- 📊 **ZEISS SMT**: production reporting on Databricks (**40% faster refresh**), scheduling optimization and an LLM analytics agent (RAG, NL-to-SQL).
- 💻 **Cognizant** (4 years): data pipelines, ML features and CI/CD for enterprise software.

MSc Data Analytics & Decision Science, RWTH Aachen. Master's thesis: *Agent-Based AI Decision Support for Process Intelligence*.

I build AI that holds up outside the demo: grounded, measured and running in production.
Open to **AI Engineer, ML Engineer, Data Scientist and Forward Deployed Engineer** roles across Germany.

🌐 Portfolio: [rahulgupta-techlok.github.io/i](https://rahulgupta-techlok.github.io/i/)

---

## Featured Projects

| Project | What it does | Result |
|---|---|---|
| [grounded-docs](https://github.com/rahulgupta-devdemo/grounded-docs) | Full-stack EN/DE document chat: React + FastAPI, Qdrant vector search, Gemini with model fallback, page-level citations; Docker Compose with nginx | Right page ranked first for 88% of 24 test questions (MRR 0.91); 8/8 unanswerable questions declined |
| [llm-security-gateway](https://github.com/rahulgupta-techlab/llm-security-gateway) | OpenAI-compatible proxy that blocks prompt injection and secret leaks and masks PII in both directions; vLLM via Docker Compose, CI | 75% detection, 0% false positives on a 24-prompt benchmark |
| [multilingual-rag-chatbot](https://github.com/rahulgupta-techlab/multilingual-rag-chatbot) | EN/DE RAG with citations and cross-lingual retrieval; hybrid BM25 + dense search with Reciprocal Rank Fusion | Cross-lingual top-1: 4/4 vs 2/4 lexical baseline |
| [llm-eval-harness](https://github.com/rahulgupta-techlab/llm-eval-harness) | Scores LLM/RAG systems on correctness, groundedness, refusal, latency and cost | Catches a hallucinating system that keyword metrics rate as perfect |
| [hybrid-search-retrieval](https://github.com/rahulgupta-techlab/hybrid-search-retrieval) | BM25 (from scratch) vs dense vs hybrid retrieval, measured with recall@k and MRR | Hybrid recall@3 = 1.0 |
| [mcp-knowledge-server](https://github.com/rahulgupta-techlab/mcp-knowledge-server) | MCP server giving agents guarded tools: read-only SQL, document search, path-traversal checks | 16 tests incl. end-to-end MCP session |
| [cloud-mlops-pipeline](https://github.com/rahulgupta-techlab/cloud-mlops-pipeline) | Trains a scikit-learn classifier and serves it through a validated FastAPI endpoint; Docker image, Kubernetes manifests | GitHub Actions runs the tests on every push; latest run passing |
| [mlops-model-monitoring](https://github.com/rahulgupta-techlab/mlops-model-monitoring) | FastAPI service that compares production batches to a reference dataset, feature by feature, using PSI and KS tests | 12 tests, incl. a deliberately shifted batch that must trip the alert (PSI > 0.2 or KS p < 0.05) |
| [streaming-pipeline-demo](https://github.com/rahulgupta-techlab/streaming-pipeline-demo) | Kafka-style producer and consumer with event-time tumbling-window aggregation, on an in-memory asyncio topic (no broker needed) | 16 tests incl. end-to-end producer-to-aggregator flow |
| [timeseries-forecasting-service](https://github.com/rahulgupta-techlab/timeseries-forecasting-service) | Forecasting API using Holt's linear trend, with MAE/RMSE backtesting on held-out data | 13 tests, incl. backtest math checked against a hand-computed example |
| [llm-tool-agent-demo](https://github.com/rahulgupta-techlab/llm-tool-agent-demo) | ReAct agent loop with a pluggable LLM interface, shipped with a rule-based stub; calculator tool uses AST parsing, never `eval` | 16 test functions incl. unsafe-input rejection; runs with no API key |

---

## Tech Stack

**AI & Machine Learning**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

**LLMs, RAG & Agents**
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google_Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square&logo=modelcontextprotocol&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white)
![vLLM](https://img.shields.io/badge/vLLM-30A2FF?style=flat-square)

**Data Engineering**
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**Backend & Frontend**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)

**Deployment & MLOps**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![nginx](https://img.shields.io/badge/nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## GitHub Stats

<p align="center">
  <img height="155" src="https://github-readme-stats.vercel.app/api?username=rahulgupta-techlab&show_icons=true&theme=dark&bg_color=0d0d0d&title_color=F97316&icon_color=F97316&text_color=ffffff&border_color=F97316&count_private=true" />
  <img height="155" src="https://github-readme-stats.vercel.app/api/top-langs/?username=rahulgupta-techlab&layout=compact&theme=dark&bg_color=0d0d0d&title_color=F97316&text_color=ffffff&border_color=F97316" />
</p>
<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=rahulgupta-techlab&theme=dark&background=0d0d0d&ring=F97316&fire=F97316&currStreakLabel=F97316&border=F97316" />
</p>

---

## Experience

| | Company | Role | Year | Type |
|---|---|---|---|---|
| 🔴 | **Bosch** | Data Scientist | 2026 |
| 🔵 | **ZEISS Group · ZEISS SMT** | Data & AI Engineer | 2025 |
| 🟠 | **FIR e.V. an der RWTH Aachen** | Research Assistant: Software Engineer and AI Agent for Decision Support | 2025-2026 |
| 🟡 | **Dr. Gaenswein Consulting** | Data Analytics & Strategy Consultant | 2025 |
| 🟢 | **Midland Credit Management** | Business Data Analyst | 2024 |
| ⚫ | **Cognizant** | Associate | 2020-2024 |

---

## Education

| | Degree | Institution | Year |
|---|---|---|---|
| 🏛️ | MSc Data Analytics & Decision Science | RWTH Aachen University | 2024-2026 |
| 🎓 | Professional Studies in Data Science and Management| IIT Madras | 2023-2024 |
| ⚙️ | B.Eng. Mechanical Engineering | IET DAVV | 2016–2020 |

---

> *"Building intelligent systems that bridge data, process, and decision."*

<p align="center">
  <a href="https://www.linkedin.com/in/rahul-gupta-49508b144/"><img src="https://img.shields.io/badge/Connect_on_LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:rahulg1397rg@gmail.com"><img src="https://img.shields.io/badge/Email_Me-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>
