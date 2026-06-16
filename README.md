# Hi, I'm Vaishnavi Kanchan

**Data Engineer** based in Germany, building data pipelines, lakehouse architectures, and streaming systems.

M.Sc. Applied Data Science and Analytics (SRH Heidelberg, 2025)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/vaishukanchan)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:kvaishu2001@gmail.com)

---

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta_Lake-00ADD8?style=flat-square&logo=databricks&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)
![Microsoft Fabric](https://img.shields.io/badge/Fabric-0078D4?style=flat-square&logo=microsoft&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![Google Cloud](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)

---

## Projects

### Data Engineering

| Project | What It Does | Stack |
|---------|-------------|-------|
| [**Energy Compliance Platform**](https://github.com/vk20001/Energy-Compliance-Platform) | CDC pipeline for German industrial electricity subsidy compliance. Row-level change capture from PostgreSQL through Debezium into Redpanda, Delta Lake medallion with SCD Type 2, 8 dbt gold models, RAG layer with NLI hallucination gate. | Debezium · Redpanda · PySpark · Delta Lake · dbt · Airflow · ChromaDB · Databricks |
| [**Finance Lakehouse on AWS**](https://github.com/vk20001/finance-lakehouse-aws) | Severity-tiered data quality governance across a three-layer lakehouse. Control-plane pattern detects CPI instability and blocks gold-layer promotion. 15 dbt models, 22 tests per run, full Terraform IaC. | AWS Lambda · S3 · Glue · Athena · dbt · Terraform · GitHub Actions |
| [**Kafka Streaming Pipeline**](https://github.com/vk20001/realtime-kafka-streaming-pipeline) | Streaming pipeline processing 17,500+ messages across 15 simulated wind turbine data streams with Pandera schema validation and live observability. | Kafka · Python · PostgreSQL · Pandera · Prometheus · Grafana |
| [**Batch ETL Pipeline**](https://github.com/vk20001/Batch-ETL-Pipeline-with-Airflow-and-dbt) | Airflow-orchestrated pipeline with 9 per-dataset Great Expectations validation suites blocking dbt transforms on failed checks. CI/CD on every push. | Airflow · dbt · Great Expectations · PostgreSQL · Docker · GitHub Actions |
| [**MetroPT Fabric Health Monitor**](https://github.com/vk20001/metropt-fabric-health-monitor) | 1.5M-row metro train compressor dataset through a Delta Lake medallion in Microsoft Fabric with quarantine patterns and z-score health scoring. | Microsoft Fabric · Delta Lake · PySpark · Power BI |
| [**Snowflake German Energy**](https://github.com/vk20001/snowflake-german-energy-intelligence) | SMARD wholesale electricity data through Snowflake Dynamic Tables with Cortex Analyst, Semantic Views, and Data Metric Functions. | Snowflake · Dynamic Tables · Cortex Analyst · Python |

### Google Gen AI Academy APAC (hack2skill x Google Cloud) | Weekly Challenge Winner | Top 50 Achiever

<img src="Track_1.png" alt="Top 50 Achiever Badge" width="120" />

**Top 50 Project Submission.** Recognized among the first 50 participants to achieve a strong score in the project submission phase.

| Project | What It Does | Stack |
|---------|-------------|-------|
| [**WindOps Assistant**](https://github.com/vk20001/wind-ops-assistant) | Multi-agent wind farm operations assistant with 5 specialist LLM agents, a coordinator, 6 workflow agents, and 25 tools across 5 FastMCP servers. Deployed live on Cloud Run. | Google ADK · Gemini 2.5 Flash · Vertex AI · Firestore · Cloud Run · FastMCP |
| [**Wind Turbine Triage Agent**](https://github.com/vk20001/wind-turbine-triage-agent) | SCADA-based fault triage agent using thesis-derived sensor thresholds. Takes raw readings, cross-references maintenance history, and produces actionable triage reports via Gemini. | Google ADK · Gemini 2.5 Flash · Vertex AI · Cloud Run |

### Data Science & ML

| Project | What It Does | Stack |
|---------|-------------|-------|
| [**TwinSolar PV Forecasting**](https://github.com/vk20001/Azure-Pv-Forecasting---TwinSolar) | LSTM-based solar power forecasting across 3 sites with 72-74% RMSE reduction. | Azure · LSTM · Python |
| [**News RAG**](https://github.com/vk20001/news-rag) | Retrieval-augmented generation pipeline with DeBERTa NLI hallucination gate for news Q&A. | ChromaDB · DeBERTa · Python |

---

## Certifications

![Microsoft](https://img.shields.io/badge/Microsoft_Fabric_Data_Engineer_Associate-0078D4?style=flat-square&logo=microsoft&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle_Cloud_Infrastructure_Architect-F80000?style=flat-square&logo=oracle&logoColor=white)
![NVIDIA](https://img.shields.io/badge/NVIDIA_Deep_Learning_Fundamentals-76B900?style=flat-square&logo=nvidia&logoColor=white)

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=vk20001&show_icons=true&theme=github_dark&hide_border=true&count_private=true" alt="GitHub Stats" />
</p>
