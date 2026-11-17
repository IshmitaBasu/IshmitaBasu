<!-- GitHub profile README for https://github.com/IshmitaBasu -->

<div align="center">

# Hi, I'm Ishmita Basu 👋

### Data Analyst · Business Intelligence · SQL & Data Modelling

**I turn messy data into reliable reports, useful business insights, and well-tested analytics workflows.**

📍 Magdeburg, Germany &nbsp;·&nbsp; 🎓 M.Sc. Data and Knowledge Engineering, Otto von Guericke University Magdeburg (expected February 2027)

[![Portfolio](https://img.shields.io/badge/Portfolio-Explore-16745E?style=flat-square&logo=githubpages&logoColor=white)](https://ishmitabasu.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ishmita-basu/)
[![Email](https://img.shields.io/badge/Email-Say%20hello-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:ishmita.basu98@gmail.com)

</div>

---

## About me

I'm a data professional with **three years of full-time BI experience at Polestar Solutions** and **nearly two years of working-student experience in market analytics at Uniper Global Commodities**. I enjoy owning a problem from the first stakeholder conversation through SQL modelling, dashboard development, validation, and handover.

At **Uniper**, I work on LNG and gas-storage analytics, Power BI reporting, and Databricks SQL solutions. Previously, at **Polestar**, I delivered client-facing BI solutions, coordinated a project team of **5–8 developers**, and mentored **eight new hires** in Power BI and SQL.

I'm also completing an M.Sc. in Data and Knowledge Engineering, where I work on **dbt/data engineering projects and research-oriented machine learning**, including an MLOps thesis on financial fraud detection. I'm interested in **full-time Data Analyst and Business Intelligence opportunities** where I can combine technical work with business understanding.

### A few results I'm proud of

- **60% faster** — proposed and independently rebuilt a quality dashboard using Databricks SQL, multi-stage CTEs, ranking logic, and conditional formatting at Uniper.
- **200+ Power BI reports** — owned delivery from requirements through UAT and handover for a major client at Polestar.
- **20% faster SQL queries** — improved reporting performance by revising schemas and fact/dimension models at Polestar.
- **35% less manual documentation effort** — created AI agent configuration files to structure Power BI dashboard information for SharePoint at Uniper.

> My approach: understand the business question, validate the data, build something people can use, and make it maintainable.

## What I work with

| Area | Tools & methods |
| --- | --- |
| **Analytics & BI** | Power BI, DAX, Power Query, KPI reporting, interactive dashboards, stakeholder communication |
| **SQL & data processing** | SQL, T-SQL, Python, Pandas, NumPy, PySpark, REST APIs, SQL CTEs |
| **Warehousing & analytics engineering** | Databricks SQL, Snowflake, BigQuery, dbt Core, Delta Lake, dimensional modelling, data tests, lineage |
| **Data platforms** | Microsoft SQL Server, Azure Data Factory, Git, GitHub, Docker |
| **Statistics & forecasting** | Exploratory analysis, ARIMA, regression, data quality checks |
| **ML & MLOps (academic projects)** | scikit-learn, LightGBM, MLflow, Feast, FastAPI, feature engineering, evaluation |
| **AI research projects** | Whisper, LoRA, Word Error Rate, multi-agent SLMs, Tree-of-Thought, Ant Colony Optimization |

## Featured projects

### 🌙 [HerRoute — Infrastructure-Aware Night Walking Routes](https://github.com/IshmitaBasu/HerRoute)
**Portfolio project · November 2026 · Berlin Alexanderplatz pilot**  
`Python` `GeoPandas` `OSMnx` `Shapely` `NetworkX` `AWS S3` `Glue` `Athena` `dbt` `GitHub Actions` `FastAPI` `Docker` `Render` `Leaflet`

Built an end-to-end geospatial data platform and public route-comparison app that compares the shortest walking route with a preference-aware alternative based on mapped public-light coverage and mapped transit-stop proximity. Created validated spatial features, versioned AWS warehouse snapshots, dbt marts and tests, GitHub OIDC-based candidate refresh and promotion workflows, and a Dockerised FastAPI application with live AWS Location address search. Evaluated **25 fixed Berlin journeys**: **24 completed**, **22 returned a feasible alternative**, with a median **66 m (2.97%)** additional distance and **+6.08 percentage-point** mapped-light coverage change. The app explicitly presents infrastructure signals as proxies, never as a safety guarantee.

[Explore project →](https://github.com/IshmitaBasu/HerRoute) · [Live demo →](https://herroute-af9y.onrender.com)

### 🛡️ [Financial Fraud Detection — Reproducible MLOps Pipeline](https://github.com/IshmitaBasu/MLOps-Pipeline-for-Fraud-Detection-in-Financial-Data)
**Master's thesis · 2026 · In progress**  
`Python` `scikit-learn` `LightGBM` `MLflow` `Feast` `FastAPI` `SQLite` `Docker`

Built a research-oriented fraud-detection workflow using **5 million transactions**, leakage-aware preprocessing, batch ingestion, versioned Feast features, and tracked model experiments in MLflow.

- Engineered sender-location history features that improved **validation Average Precision by 5.69% relative to the control** in a controlled comparison.
- Verified **research-only** API serving and batch-monitoring checks.
- Treat this as an experimental MLOps system, **not a production-ready fraud detector**; validation gains should not be confused with held-out test performance.

[Explore project →](https://github.com/IshmitaBasu/MLOps-Pipeline-for-Fraud-Detection-in-Financial-Data)

### 🧱 [Retail Sales & Operations Analytics Lakehouse](https://github.com/IshmitaBasu/retail-sales-operations-lakehouse)
**Portfolio project · November 2026 · Synthetic data**  
`dbt Core` `Databricks SQL` `Delta Lake` `SQL` `Python` `Power BI` `Docker` `PostgreSQL` `n8n` `Streamlit`

Built a dbt/Databricks retail lakehouse with incremental Delta `MERGE` processing, tested dimensional marts, and documented lineage. Delivered a **four-page Power BI dashboard** for sales, products, customers, and fulfilment. Added automated dbt failure monitoring with incident grouping, rule-based triage, GitHub/email alerts, and an isolated candidate-validation gate; **305 candidate checks passed** before human-reviewed release.

[Explore project →](https://github.com/IshmitaBasu/retail-sales-operations-lakehouse)

### ⚡ [Energy Subscription Analytics — dbt + BigQuery](https://github.com/IshmitaBasu/Energy-Subscription-Analytics)
**Portfolio project · November 2026 · Synthetic data**  
`dbt Core` `BigQuery` `SQL` `MetricFlow` `Docker` `Metabase`

Defined dimensional grains and revenue/contract metrics for energy-subscription reporting. Added **123 data tests and four unit tests**, documented MetricFlow metrics, and built a Metabase dashboard on curated marts.

[Explore project →](https://github.com/IshmitaBasu/Energy-Subscription-Analytics)

### 🐝 [Swarm SLM Agents — Calendar Planning](https://github.com/IshmitaBasu/Swarm-Planner-Agent)
**Team project · November 2025 – April 2026**  
`Multi-agent SLMs` `Tree-of-Thought` `Ant Colony Optimization` `Evaluation`

Co-developed a decentralised scheduling approach combining a five-stage Tree-of-Thought process with ACO-inspired branch selection. Across **400 NaturalPlanner tasks**, the exact-match solve rate increased from **24.75% to 40.0%**; the Tree-of-Thought variant without ACO achieved **39.5%**.

[Explore project →](https://github.com/IshmitaBasu/Swarm-Planner-Agent)

### 🎙️ [Multilingual Speech Recognition — Whisper Fine-Tuning](https://github.com/IshmitaBasu/whisper-fine-tune-low-resource-language)
**Academic project · March – May 2025**  
`Python` `Whisper` `LoRA` `WER Evaluation`

Fine-tuned Whisper for **Bengali and Telugu** using LoRA, compared Word Error Rate before and after adaptation, and studied performance under background noise while exploring speaker diarisation.

[Explore project →](https://github.com/IshmitaBasu/whisper-fine-tune-low-resource-language)

<details>
<summary><b>More projects</b></summary>

<br>

- **Bundestag-MINE — Personalized Speech Recommendations (2024–2025):** Built React/TypeScript interfaces, integrated recommendation outputs, wrote tests, and fixed user-facing defects in a parliamentary-speech research prototype.
- **Physician vs. AI Assessment Study (2024):** Analysed structured questionnaire responses using descriptive statistics and Power BI to visualise assessment differences.
- **[Power BI Data Visualization](https://github.com/IshmitaBasu/PowerBI-Project):** Sample-data reporting and visual analytics.
- **[Auto-Subtitle Generation](https://github.com/IshmitaBasu/Auto-Subtitle-Generation):** Python-based subtitle-generation project.

</details>

## Professional experience

### Uniper Global Commodities SE — Working Student, Market Analyst
*April 2025 – present · Düsseldorf, Germany*

- Proposed and independently rebuilt a Norwegian-model quality dashboard in **Databricks SQL**, reducing load time by **60%** and explaining the implementation to colleagues.
- Developed and enhanced **gas-storage and LNG Power BI dashboards**, using DAX, bookmarks, conditional formatting, drill-down, and drill-through; became a go-to contact for Power BI enhancements.
- Extended **Asian LNG analytical models** by updating Python calculation logic, base tables, and API-derived inputs connected to Databricks Catalog tables.
- Built **three additional Power BI dashboards** for model error/ranking reviews and used **Snowflake SQL and Power Query** to process nested JSON and investigate inconsistent values.
- Automated repetitive dashboard documentation for business users with **AI agent configuration files**, cutting manual effort by **35%**.

### Polestar Solutions and Services India Pvt. Ltd. — Senior Data Analyst
*February 2021 – March 2024 · Kolkata, India*

- Owned end-to-end delivery of **200+ Power BI reports**, including requirements, development, client reviews, UAT, and handover; implemented **row-level security and Power Apps integration**.
- **Led project delivery for 5–8 Power BI developers** on an African pharmaceutical engagement, coordinating assignments, reviewing SQL/report logic, and incorporating stakeholder feedback.
- **Trained and mentored eight new hires** in Power BI and SQL through hands-on exercises and query reviews.
- Reworked schemas and fact/dimension models, improving SQL execution time by **20%**; built Python and Azure data-preparation pipelines for reporting.
- Investigated reporting discrepancies through source-to-report validation; applied **ARIMA and regression** to social-media engagement analysis.

### PwC India — Trainee
*June – July 2018 · Kolkata, India*

- Developed a **C# restaurant-registration interface** backed by SQL tables and queries, and documented the implementation for testing and handover.

> Employer work is described at a high level to respect client confidentiality. Public repositories primarily showcase academic and personal portfolio projects.

## Education & languages

- 🎓 **M.Sc. Data and Knowledge Engineering**, Otto von Guericke University Magdeburg — *April 2024 – February 2027 (expected)*
- 🎓 **B.Tech. Information Technology**, Techno India Saltlake — *August 2016 – July 2020*
- 🌍 **Languages:** English (C2/fluent) · Bengali (native) · German (A2)

## Let's connect

I'm interested in practical **analytics, BI, SQL/data modelling, and analytics engineering**—and in making data products understandable to the people who use them.

📩 **[Email](mailto:ishmita.basu98@gmail.com)** · 💼 **[LinkedIn](https://www.linkedin.com/in/ishmita-basu/)** · 🌐 **[Portfolio](https://ishmitabasu.github.io/)**

---

<div align="center"><sub>Thanks for visiting! ✨</sub></div>
