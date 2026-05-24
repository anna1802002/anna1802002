# Hi, I'm Ananya Shetty 👋

🎯 **AI Engineer & Analytics Engineer** | Building agentic AI systems and the data infrastructure behind them.

📍 Boston, MA &nbsp;|&nbsp; Open to full-time **AI Engineer / Data Engineer / Analytics Engineer / Data Analyst** roles 

---

## 🧰 Tech Stack

**AI / LLM Systems**

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat&logo=langchain&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-FF6F61?style=flat&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat&logoColor=white)
![Weaviate](https://img.shields.io/badge/Weaviate-00C7B7?style=flat&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=flat&logo=neo4j&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat&logoColor=white)

**Data Engineering**

![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat&logo=dbt&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat&logo=snowflake&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat&logo=apache-airflow&logoColor=white)
![Dagster](https://img.shields.io/badge/Dagster-654FF0?style=flat&logoColor=white)
![Prefect](https://img.shields.io/badge/Prefect-024DFD?style=flat&logo=prefect&logoColor=white)

**Languages & Frameworks**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)

**Cloud & DevOps**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=github-actions&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=flat&logo=opentelemetry&logoColor=white)

---

## 🚀 Featured Projects

### 💼 [EquityLens — AI Equity Research Platform](https://github.com/anna1802002/equitylens)

Live AI agent that turns any stock ticker into a Wall Street-style equity research report (Buy/Hold/Sell, 12-month price target, bull/bear cases, risk score) in under 2 minutes. Built on a 5-stage LangGraph pipeline with a multi-agent investment committee (bull, bear, risk officer) reviewing every recommendation in parallel.

Benchmarked on 150 FinanceBench QA pairs: **87.5% factual accuracy, 4.2% hallucination rate, 0.73 ROUGE-L** versus baseline GPT (61.2%, 18.7%, 0.48). Eliminates look-ahead bias in financial RAG through point-in-time correctness on every historical query.

`LangGraph` · `AutoGen` · `FinBERT` · `Pinecone` · `Groq/Llama 3.1` · `FastAPI` · `Next.js 14` · `Neo4j` · `Upstash Redis`

---

### 🎥 [VidSynth — YouTube Video Analysis Chrome Extension](https://github.com/anna1802002)

6-microservice video analysis backend (gateway, read, preprocess, llm, validate, push) orchestrated by Airflow, fronted by a Chrome extension. Re-architected the gateway from a synchronous DAG trigger to an event-driven flow via Redpanda so memory writes and telemetry no longer block user requests.

Added a Weaviate-backed memory layer for context reuse on related queries, plus OpenTelemetry distributed tracing and a Prometheus metrics endpoint for root-cause visibility across services. **Demoed at Google Office, Cambridge, MA.**

`FastAPI` · `Airflow` · `Redpanda (Kafka)` · `Weaviate` · `OpenTelemetry` · `Prometheus` · `DVC`

---

### 📦 [SupplySync — Supply Chain Analytics Platform](https://github.com/anna1802002/SupplySync-Analytics-Platform)

Supply-chain analytics platform that pairs SKU-level demand forecasting with constraint optimization, producing concrete reorder recommendations under capacity and lead-time constraints — instead of leaving buying teams to guess from raw forecasts.

Tracks 4 governed KPIs (inventory turnover, stockout rate, lead-time variance, fill rate) modeled in dbt with schema tests, range tests, and source-freshness alerts. Full pipeline runs as scheduled asset jobs in Dagster, gated by a GitHub Actions CI workflow.

`Python` · `dbt Core` · `Dagster` · `Nixtla StatsForecast` · `OR-Tools` · `Great Expectations`

---

### 🏥 [End-to-End Healthcare Data Pipeline](https://github.com/anna1802002/End-to-end-healthcare-data-pipeline)

Compliance-first healthcare ETL pipeline producing FHIR-compliant outputs for downstream interoperability. Column-level masking plus cryptographic encryption applied to 5 sensitive PHI fields (name, email, phone, address, SSN), with raw PHI dropped post-transform.

Defense-in-depth validation at 3 boundaries: pandera schema contracts at ingest, FHIR shape validation at mapping, Soda data-quality checks over curated outputs — all gated by CI.

`Prefect` · `pandera` · `Soda` · `cryptography` · `FHIR JSON` · `Parquet` · `MongoDB` · `AWS S3`

---

## 📊 GitHub Stats

![Ananya's GitHub Stats](https://github-readme-stats.vercel.app/api?username=anna1802002&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117&title_color=F0A500&icon_color=F0A500)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=anna1802002&layout=compact&theme=dark&hide_border=true&bg_color=0d1117&title_color=F0A500)

---

## 📫 Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ananyashetty18/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:shetty.ana@northeastern.edu)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/anna1802002)
