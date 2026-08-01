<div align="center">

# Lakshmi Bharathy Kumar

**Data Scientist** — Turning Complex Data into Business Decisions

M.S. Applied Data Intelligence, San José State University (May 2026) · 2 years marketing analytics experience
· Open to work · Authorized to work in the U.S. without sponsorship

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=googlechrome&logoColor=white)](https://lakshmibharathy11.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lakshmi-bharathy-kumar/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:lakshmibharathyk@gmail.com)

</div>

---

## About

I take messy, real-world data and turn it into decisions a business can act on. That means three things, in order: understanding the data well enough to trust it, building the right model for the question (statistical, causal, ML, or LLM-based), and making sure it actually runs somewhere — not just in a notebook.

Concretely: I've built Bayesian models that told a marketing team where to move $4.8M in ad spend, a churn model that identified which 1% of customers to protect to save 25% of projected revenue, and a full agentic AI system with a human-in-the-loop safety gate before anything reaches a customer. I've also shipped that work as containerized APIs and scheduled pipelines, not just analysis — because a model that only runs on my laptop isn't useful to a company yet.

Before graduate school, I spent two years at RepuNEXT doing marketing analytics — diagnosing funnel drop-off and rebuilding SEO targeting, which grew organic traffic 25%. That's the throughline in everything below: I don't build models to build models. I build them to change an outcome.

---

## Core Data Science & Modeling

*Statistics, causal inference, and applied ML — the primary focus of my target roles.*

| Project | What it does | Result |
|---|---|---|
| **[Marketing Mix Modeling — Budget Allocator](https://github.com/Lakshmibharathy11/Marketing-Mix-Modeling-for-Multichannel-Budget-Allocation)** | Bayesian model (Google Meridian) recommending how to split ad budget across 5 channels, using 156 weeks of geo-level data | **$4.8M** recommended reallocation, +0.5% projected conversion lift |
| **[Causal Uplift & Incrementality Modeling](https://github.com/Lakshmibharathy11/Causal-Uplift-Budget-Optimizer)** | Identifies which of 1M+ users an ad campaign actually changes the mind of, vs. who would've bought anyway | Naive targeting wastes ~22% of spend · **+14%** incremental conversions at equal budget |
| **[Retention Priority Dashboard: RFM, CLV & Churn Risk](https://github.com/Lakshmibharathy11/Retention-Priority-Dashboard-RFM-CLV-and-Churn-Risk)** | Combines customer value and churn risk into one ranked "who's worth saving" list, not just a churn score | Top 50 customers (<1% of base) represent **£9.26M**, 24.7% of total customer value |
| **[Gaze-Based Intent Classification](https://github.com/Lakshmibharathy11/Graduate_Thesis)** *(M.S. Thesis)* | Predicts where a person is looking from eye-tracking sensor data, for hands-free assistive device control | **0.94** cross-user accuracy, 12pp above published baseline · manuscript in preparation |

---

## Applied AI & Data Engineering

*Getting data from raw source to model-ready — pipelines, orchestration, and applied ML on operational data.*

| Project | What it does | Result |
|---|---|---|
| **[Tesla Stock Sentiment Pipeline](https://github.com/Lakshmibharathy11/Tesla_stock_sentiment_analysis)** *(group project, DATA226)* | End-to-end ELT pipeline combining stock price data with tweet sentiment | R² = 0.916 · my contributions: sentiment scoring, Snowflake ELT, SQL regression, Airflow, dbt |
| **[Law Enforcement Response Analytics](https://github.com/Lakshmibharathy11/Law_Enforcement_Analytics)** | Automated ETL pipeline ranking police districts by call response time, orchestrated daily | Airflow + dbt + Snowflake, fully containerized, with automated data quality tests |
| **[Developer Salary Prediction](https://github.com/Lakshmibharathy11/Salary-Prediction)** | Predicts developer compensation from skills, role, and demographics using 5 years of Stack Overflow survey data | R² = 0.62 · 90K+ responses · interactive Power BI prediction dashboard |

---

## Production Engineering & Applied Systems

*Shipping models and AI systems as real, running software — APIs, containers, and cloud deployment.*

| Project | What it does | Result |
|---|---|---|
| **[AI Support Ticket Triage Agent](https://github.com/Lakshmibharathy11/AI-Customer-Support-Triage-Agent)** | 8-node LangGraph agent that classifies, retrieves, drafts, and self-evaluates support responses, with a human approval gate before anything risky ships | Faithfulness 0.81 · $0.00139/ticket · real HITL interrupt, not simulated |
| **[Plate Planner API](https://github.com/Lakshmibharathy11/plate-planner-api-main)** | FastAPI service backed by a Neo4j graph database and semantic embeddings, recommending recipes and ingredient substitutions | Fully Dockerized · FAISS + SentenceTransformers for semantic matching |
| **[Multimodal Multi-Agent Image Editing Pipeline](https://github.com/Lakshmibharathy11/Multimodal-RAG-System-for-PDF-Q-A)** | 4-agent LangGraph workflow (vision understanding → prompt refinement → generation → critique) that edits images and retries when its own evaluation isn't satisfied | 12/12 runs completed · avg rubric score 4.03/5 · CLIP image-similarity 0.938 |
| **[Bay Area Job Monitor](https://github.com/Lakshmibharathy11/job-search-assistant)** | Automated pipeline scanning startup job boards for relevant new-grad roles, with scam detection and dedup logic | Diagnosed and fixed a scheduling bug causing ~500 wasted runs/week, cut to 4/week · GitHub Actions CI |
| **[Distributed User Management System](https://github.com/Lakshmibharathy11/Distributed-User-Management-System---Node.js-React-MySQL-Docker-AWS-ECS)** | Full-stack CRUD web app with API validation, deployed as a containerized service | Node.js · React · MySQL · Docker · AWS ECS |

---

## Tech Stack

**Statistics & Causal Inference**
![Bayesian](https://img.shields.io/badge/Bayesian_Inference-4B0082?style=flat-square)
![MCMC](https://img.shields.io/badge/MCMC-4B0082?style=flat-square)
![Causal](https://img.shields.io/badge/Causal_Inference-4B0082?style=flat-square)
![AB](https://img.shields.io/badge/A/B_Testing-4B0082?style=flat-square)
![Uplift](https://img.shields.io/badge/Uplift_Modeling-4B0082?style=flat-square)

**Languages & ML**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=flat-square)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Statsmodels](https://img.shields.io/badge/Statsmodels-white?style=flat-square)

**Data Engineering & Cloud**
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

**Production & APIs**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-008CC1?style=flat-square&logo=neo4j&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)

**Applied AI Tooling**
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-1C3C3C?style=flat-square)
![Ragas](https://img.shields.io/badge/Ragas-4B0082?style=flat-square)

**Visualization & BI**
![PowerBI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Looker](https://img.shields.io/badge/Looker_Studio-4285F4?style=flat-square&logo=google&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

---

## Education

**M.S. Applied Data Intelligence** — San José State University *(May 2026)*
Bayesian Inference · Causal Inference · Machine Learning · Big Data Analytics

**B.E. Electronics & Communication Engineering** — Saranathan College of Engineering, India *(May 2014)*

## Experience

**Digital Marketing Specialist** — RepuNEXT, Chennai *(Jun 2021 – Dec 2022)*
Analytics and automated reporting across client accounts using Google Analytics and SEMrush · grew organic traffic 25% · built reporting workflows that improved campaign ROI 15%

---

<div align="center">

**Seeking Data Scientist, Marketing/Growth Analytics, or Analytics Engineering roles in the Bay Area**

[Portfolio](https://lakshmibharathy11.github.io) · [LinkedIn](https://www.linkedin.com/in/lakshmi-bharathy-kumar/) · [Email](mailto:lakshmibharathyk@gmail.com)

</div>
