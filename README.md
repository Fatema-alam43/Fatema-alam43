# Hi, I'm Fatema 👋

**Machine Learning & Data Engineering · MEng student at McMaster University · Seeking a Co-op from January 2027**

I build ML systems that hold up in the real world, not just in a notebook. I test my models on data they have never seen, catch problems like data leakage before they reach production, and measure my AI apps for wrong or made-up answers.

I bring 2+ years of industry experience as a Data Analyst and Backend Developer Intern, plus experience teaching ML to 150+ students. Now I build end-to-end projects, from raw data to deployed models and AI agents.

📍 Hamilton, Ontario · ☁️ AWS Certified Cloud Practitioner · 🎓 MEng, Automation Systems and Technology · GPA 3.9/4.0

📅 **Available for a 4, 8 or 12-month co-op starting January 2027**

---

## 💼 Experience

### Data Analyst · DOT-IT, Bangladesh
*Jan 2024 – May 2025*
- **Automated weekly reporting** with Python and SQL over 50,000+ server log records, cutting preparation time from 3 hours to 15 minutes for product and technical leads
- **Built data-quality checks** (duplicates, ranges and anomalies) for operational data, reducing reporting errors by about 30%
- **Trained a churn model** on 15,000 customer records that found subscription inactivity as the main reason customers left, guiding re-engagement campaigns

### Backend Developer Intern · bongoDev, Bangladesh
*Apr 2023 – Nov 2023*
- **Gathered requirements** with stakeholders and wrote user stories in an Agile team
- **Shipped 10 REST API endpoints** in Node.js and Express for course enrollment and student progress, each going live after peer code review
- **Wrote 15 Jest tests** for those endpoints, reaching 85% test coverage and catching edge-case bugs before release

### ML Workshop Instructor & Teaching Assistant (Part-time) · BAIUST, Bangladesh
*Sep 2022 – May 2025*
- **Designed and taught 8 hands-on ML workshops** for 150+ undergraduates on scikit-learn, model training and evaluation
- **Mentored 30 student ML projects** to a 93% completion rate; strong feedback led the department to keep running the workshops

---

## 🚀 Featured projects

### 💊 Medic AI: Healthcare RAG Assistant and AI Agent
An AI assistant that answers questions only from 15 FDA drug labels and cites the source for every answer. I extended it into a LangChain agent with 3 tools (label search, two-drug comparison, dose-time calculator), with guardrails that refuse out-of-scope questions.
- **Tested, not just demoed:** 22-question evaluation logged in SQLite, with 18/22 fully correct, 0 failures and 0 hallucinated answers
- **Agent accuracy:** chose the right tool in 4 of 5 tests
- **Honest about limits:** documented two failure modes, a retrieval gap and incomplete list answers

`Python` `LangChain` `Gemini` `Groq` `ChromaDB` `Hugging Face` `SQLite` `Gradio`

[Repo](https://github.com/Fatema-alam43/healthcare-ai-rag-assistant)

### 🚕 NYC Taxi Trip Duration: End-to-End ML Pipeline
Predicts trip duration on 1.46M trips with LightGBM, cutting error by 23.6% (MAE 224 → 171 s, R² 0.80), and validated on a future month the model never saw.
- **Caught a hidden bug:** found target leakage that made a baseline look 13× better than reality, then blocked it with data contracts and tests
- **Shipped to production:** FastAPI service in Docker on AWS Lambda with a live demo, 91 tests, CI and weekly retraining
- **Scaled on Azure:** moved the pipeline to Azure Databricks with keyless access, with results matching exactly across four engines

`Python` `PySpark` `DuckDB` `LightGBM` `SHAP` `MLflow` `FastAPI` `Docker` `AWS Lambda` `Azure Databricks` `Prefect` `GitHub Actions`

[Repo](https://github.com/Fatema-alam43/ml-pipeline-nyc-taxi-trip-duration) · [Live demo](https://fatema-alam43.github.io/ml-pipeline-nyc-taxi-trip-duration/)

### 📊 Employee Attrition Risk Prediction (research, team of 2)
A leakage-free attrition model built with nested cross-validation and corrected statistical tests. Removing hidden leakage gave honest results, and calibration cut expected calibration error by 87%. Manuscript in preparation.

`scikit-learn` `XGBoost` `CatBoost` `EBM` `SHAP` `Conformal prediction` `Streamlit`

### ☁️ Cloud Healthcare Data Pipeline on AWS
Moves 5,110 patient records from raw CSV to a Power BI dashboard through S3, RDS PostgreSQL, Athena and Glue. Imputed missing values without dropping a single record, and found stroke rates rising from 0.13% under age 30 to 17.75% at 70+.

`AWS S3` `RDS PostgreSQL` `Athena` `Glue` `Python` `SQL` `Power BI`

[Repo](https://github.com/Fatema-alam43/aws-s3-athena-rds-powerbi-healthcare-pipeline)

### 🏥 Healthcare Analytics Platform (SQL + Power BI)
Turned a flat file of 55,500 records into a normalized PostgreSQL schema with zero orphaned records, then wrote SQL with joins, CTEs and window functions to feed a Power BI dashboard with data-quality checks.

`Python` `pandas` `PostgreSQL` `SQL` `Power BI` `DAX`

[Repo](https://github.com/Fatema-alam43/healthcare-analytics-platform_SQL_PowerBI)

### 👁️ Azure AI Vision OCR Demo
A Python app that reads text and tags from document images, capturing all 34 lines of a scanned book page with punctuation intact. Keys stay out of the public repo.

`Python` `Azure AI Vision` `Azure SDK`

[Repo](https://github.com/Fatema-alam43/azure-vision-ocr-demo)

---

## 🛠️ Tech stack

**Machine learning:** scikit-learn · LightGBM · XGBoost · CatBoost · PyTorch · Hugging Face · SHAP · time-series forecasting (ARIMA) · clustering and anomaly detection · model calibration

**Generative AI:** LangChain agents · RAG · MCP · ChromaDB · Gemini · Groq · Azure OpenAI · LLM evaluation

**Data engineering:** Python · SQL · PySpark · DuckDB · pandas · Airflow · Prefect · Parquet · ETL

**MLOps and deployment:** MLflow · FastAPI · Docker · pytest · GitHub Actions · Databricks Asset Bundles

**Cloud:** AWS (S3, RDS, Athena, Glue, Lambda, ECR) · Azure (Databricks, Data Factory, AI Vision, OpenAI)

**Databases and BI:** PostgreSQL · SQL Server · SQLite · MongoDB · Power BI · DAX · Tableau

**Other:** Node.js · Express · Jest · Jira · Agile (Scrum, user stories)

---

## 🌱 Right now

- Building a vision-language model that answers questions about images and learns when not to answer (Deep Learning course team project)
- Turning my attrition project into a research paper
- Looking for a **co-op from January 2027** in ML engineering, AI engineering, data science or data engineering

## 🤝 Let's connect

[LinkedIn](https://www.linkedin.com/in/fatema-alam-074496249/) · [Email](mailto:alamf14@mcmaster.ca)

Outside of code, you'll find me on long walks and trying desserts at coffee shops around Hamilton. Recommendations welcome!
