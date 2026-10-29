<div align="center">

# Lakshmi Bharathy Kumar

**Data & Product Analyst · Associate Data Scientist**

Turning User Data into Business ROI · A/B Testing | Data & Product Analytics | Causal ML

M.S. Applied Data Intelligence, San José State University (May 2026) · San Jose, CA · Bay Area & Remote
Authorized to work in the U.S. without sponsorship

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=googlechrome&logoColor=white)](https://lakshmibharathy11.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lakshmibharathy-kumar)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:lakshmibharathy.kumar@gmail.com)

</div>

---

## About

I use SQL, Python, experimentation, and causal ML to answer the question behind the dashboard: **what actually drove the result, and what should we do next?**

My foundation is two years of hands-on marketing and web analytics for client businesses, where I diagnosed funnel drop-off, defined KPIs, and reported results to founders and managing directors. My M.S. in Applied Data Intelligence added the rigor to test changes properly, measure true incrementality, and prioritize the customers worth keeping. I also build the pipelines and tools that make that analysis repeatable.

---

## Featured Work

*Projects that answer real business questions: where to spend, who to target, which customers to keep, and what changed this week and why.*

| Project | Business question | Result |
|---|---|---|
| **[Weekly Business Review (WBR) AI Agent](https://github.com/Lakshmibharathy11/team-s04-wbr-agent-mirror)** 🏆 *AWS Agentic AI Hackathon Finalist* | Why did this week's e-commerce metrics move? An analyst agent investigates metric changes with SQL query tools and robust z-score anomaly detection; a verifier agent checks every claim before the memo reaches a reader | **Top 5 of 12** teams, presented live at AWS Community Day Bay Area · 283 automated tests · 13/13 queries match between DuckDB and AWS Athena |
| **[Causal Uplift & Incrementality Platform](https://github.com/Lakshmibharathy11/Causal-Uplift-Budget-Optimizer)** | Which users convert *because* of an ad, versus users who would have converted anyway? Uplift models on the Criteo dataset (13.9M users), deployed as a Streamlit tool on AWS EC2 | **87.8%** of incremental conversions captured by targeting the top 30% of users · 13.2% of users identified as persuadables · Qini 0.726 |
| **[Bayesian Marketing Mix Model & Budget Optimizer](https://github.com/Lakshmibharathy11/Marketing-Mix-Modeling-for-Multichannel-Budget-Allocation)** | Which channels actually drive revenue, and how should a fixed budget be split? Built with Google Meridian on its simulated demo dataset (156 weeks, 5 paid channels) | **$7.7M** reallocated at the same $219.5M budget · **+0.35%** projected media-driven revenue · 4.4% MAPE |
| **[Customer Retention Priority Engine: RFM, CLV & Churn](https://github.com/Lakshmibharathy11/Retention-Priority-Dashboard-RFM-CLV-and-Churn-Risk)** | Which customers are worth the retention budget? Combines customer value and churn risk into one ranked list (Online Retail II, ~5,878 customers) | Top 50 customers (<1% of base) hold **£9.26M**, 24.7% of projected value · found and removed data leakage before finalizing the churn model |

---

## Graduate Research

| Project | What it does | Status |
|---|---|---|
| **[Eye-Tracking Based Direction Control Using Machine Learning Technique](https://github.com/Lakshmibharathy11/Graduate_Thesis)** *(M.S. Thesis)* | Classifies gaze direction from lab-collected eye-tracking data for hands-free assistive control, tested on both familiar and new users | Published on SJSU ScholarWorks · [DOI 10.31979/etd.h3rd-h8n2](https://doi.org/10.31979/etd.h3rd-h8n2) · 1-minute overview video in the repo |

---

## Data Pipelines & Statistical Modeling

| Project | What it does | Result |
|---|---|---|
| **[Law Enforcement Data ETL Pipeline](https://github.com/Lakshmibharathy11/Law_Enforcement_Analytics)** | Solo-built ELT pipeline: a daily Airflow DAG loads police dispatch records into Snowflake, and dbt models rank districts by response time | Airflow + dbt + Snowflake, containerized with Docker Compose, with dbt data tests |
| **[Tesla Stock Sentiment Pipeline](https://github.com/Lakshmibharathy11/Tesla_stock_sentiment_analysis)** *(group project, DATA 226)* | Combines stock prices with tweet sentiment in an ELT pipeline | R² = 0.916 · my part: VADER sentiment, Snowflake ELT, SQL regression, Airflow, dbt |
| **[Developer Salary Prediction](https://github.com/Lakshmibharathy11/Salary-Prediction)** *(DATA 230)* | Predicts developer pay from Stack Overflow survey data (2020–2024) | R² = 0.62 · RMSE ~$31K · Power BI prediction dashboard |

---

## Applied AI & Engineering

| Project | What it does | Result |
|---|---|---|
| **[AI Customer Support Triage Agent](https://github.com/Lakshmibharathy11/AI-Customer-Support-Triage-Agent)** | LangGraph agent that classifies tickets, retrieves from a knowledge base (FAISS), drafts and self-evaluates answers, with a human approval gate for low-faithfulness responses | Faithfulness 0.81 · relevance 0.94 (LLM-as-judge) · $0.00139 per ticket across 45 tickets |
| **[Bay Area Job Monitor](https://github.com/Lakshmibharathy11/job-search-assistant)** | GitHub Actions pipeline that pulls new roles from job APIs, filters and scores them, flags likely scam postings, and sends email and WhatsApp digests | Found and fixed a disabled scheduling guard, cutting runs from ~500/week to 4/week |
| **[Kayak-Style Travel Booking Platform](https://github.com/Lakshmibharathy11/Kayak_style_full_stack_development)** *(team project, DATA 236)* | Full-stack booking system: React/TypeScript frontend, 8 FastAPI microservices, Kafka event streaming | My parts: booking module, billing middleware, Kafka booking topics, MySQL data, concierge agent |
| **[Multimodal Multi-Agent Image Editing Pipeline](https://github.com/Lakshmibharathy11/Multimodal-RAG-System-for-PDF-Q-A)** | LangGraph workflow (vision understanding → prompt refinement → editing → critique) that retries when its own evaluation isn't satisfied | 12/12 runs completed · avg rubric score 4.03/5 · CLIP image similarity 0.938 |
| **[Plate Planner API](https://github.com/Lakshmibharathy11/plate-planner-api-main)** | FastAPI service on a Neo4j graph with semantic embeddings for recipe recommendations and ingredient substitutions | Dockerized · FAISS + SentenceTransformers |

---

## Tech Stack

**Experimentation & Causal Inference**
![AB](https://img.shields.io/badge/A%2FB_Testing-4B0082?style=flat-square)
![Causal](https://img.shields.io/badge/Causal_Inference-4B0082?style=flat-square)
![Uplift](https://img.shields.io/badge/Uplift_Modeling-4B0082?style=flat-square)
![Bayesian](https://img.shields.io/badge/Bayesian_Inference-4B0082?style=flat-square)
![MCMC](https://img.shields.io/badge/MCMC-4B0082?style=flat-square)

**Languages & ML**
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Statsmodels](https://img.shields.io/badge/Statsmodels-555555?style=flat-square)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=flat-square)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)

**Data Engineering & Cloud**
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS_%28S3%2C_EC2%2C_Athena%2C_Bedrock%29-232F3E?style=flat-square&logo=amazonaws&logoColor=white)

**BI & Visualization**
![Looker](https://img.shields.io/badge/Looker_Studio-4285F4?style=flat-square&logo=google&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)
![PowerBI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![GA](https://img.shields.io/badge/Google_Analytics-E37400?style=flat-square&logo=googleanalytics&logoColor=white)

**Applied AI**
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-1C3C3C?style=flat-square)
![LLMEval](https://img.shields.io/badge/LLM_Evaluation-1C3C3C?style=flat-square)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

---

## Experience

**Digital Marketing Specialist** · RepuNEXT, Chennai *(Jun 2021 – Dec 2022)*
Analytics, SEO, and paid search for four client accounts · diagnosed funnel drop-off with Google Analytics and SEMrush, contributing to a 25% increase in organic traffic · prioritized website changes through funnel analysis, improving campaign ROI by 15%

**Marketing Analyst** · Web Digital Mantra, Bangalore *(Aug 2020 – Jan 2021)*
Monthly website analytics and user-metrics reports and dashboards for five clients, presented to client stakeholders

## Education

**M.S. Applied Data Intelligence** · San José State University *(May 2026)*

**B.E. Electronics & Communication Engineering** · Saranathan College of Engineering, India *(May 2014)*

---

<div align="center">

**Open to Data Analyst, Product Analyst, and Associate Data Scientist roles in the Bay Area or remote**

[Portfolio](https://lakshmibharathy11.github.io) · [LinkedIn](https://www.linkedin.com/in/lakshmibharathy-kumar) · [Email](mailto:lakshmibharathy.kumar@gmail.com)

</div>
