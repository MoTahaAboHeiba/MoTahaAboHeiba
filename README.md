<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=700&size=28&duration=3000&pause=1000&color=38C2BF&center=true&vCenter=true&width=750&lines=Mohamed+Taha+Abo+Heiba;Data+Engineer;Cloud+%7C+ETL+%7C+Big+Data" alt="Typing SVG" />

<a href="mailto:mohamed-aboheiba@outlook.com"><img src="https://img.shields.io/badge/Email-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/mohamed-taha-abo-heiba/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://motahaaboheiba.github.io"><img src="https://img.shields.io/badge/Portfolio-111827?style=for-the-badge&logo=github&logoColor=white"/></a>

<img src="https://komarev.com/ghpvc/?username=MoTahaAboHeiba&label=Profile+Views&color=38C2BF&style=flat" />

</div>

---

## How I Think About Data Engineering

I treat data infrastructure as a systems problem: correctness before performance, observability from day one, and hard boundaries between pipeline layers. A pipeline that runs once is not the same as one that runs reliably at scale.

My work spans batch ETL on Databricks, streaming with Kafka and Flink, SQL Server warehouses built on stored-procedure layers, and production RAG APIs with offline evaluation harnesses. The same rigor applies everywhere.

---

## Current Focus

- Medallion Architecture pipelines on Databricks and Delta Lake
- Cloud-native data platforms on AWS — Glue, Redshift, EMR, Athena
- DE for AI workflows — vector indexing, hybrid retrieval, and retrieval evaluation
- ETL orchestration with Apache Airflow

---

## Tech Stack

<div align="center">

**Core**

<img src="https://skillicons.dev/icons?i=python,mysql,postgresql,docker,bash,git,github&perline=7" />

**Big Data & Processing**

<img src="https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white"/>
<img src="https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white"/>
<img src="https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white"/>
<img src="https://img.shields.io/badge/Delta%20Lake-00ADD8?style=for-the-badge&logo=databricks&logoColor=white"/>
<img src="https://img.shields.io/badge/Hadoop-66CCFF?style=for-the-badge&logo=apachehadoop&logoColor=black"/>
<img src="https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white"/>
<img src="https://img.shields.io/badge/Flink-E6526F?style=for-the-badge&logo=apacheflink&logoColor=white"/>

**Orchestration & Storage**

<img src="https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white"/>
<img src="https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white"/>
<img src="https://img.shields.io/badge/Unity%20Catalog-FF3621?style=for-the-badge&logo=databricks&logoColor=white"/>

**Cloud — AWS**

<img src="https://img.shields.io/badge/S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white"/>
<img src="https://img.shields.io/badge/Glue-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white"/>
<img src="https://img.shields.io/badge/Redshift-8C4FFF?style=for-the-badge&logo=amazonredshift&logoColor=white"/>
<img src="https://img.shields.io/badge/EMR-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white"/>
<img src="https://img.shields.io/badge/Athena-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white"/>
<img src="https://img.shields.io/badge/EC2%20%7C%20RDS%20%7C%20Lambda%20%7C%20IAM-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white"/>

**AI Data Engineering**

<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white"/>
<img src="https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/ChromaDB-FF6B35?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>

**Analytics & BI**

<img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
<img src="https://img.shields.io/badge/DAX-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
<img src="https://img.shields.io/badge/Power%20Query-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>

</div>

---

## Featured Projects

### E-Commerce Lakehouse — Databricks & Delta Lake

End-to-end lakehouse pipeline processing 200K+ records through Medallion Architecture (Bronze → Silver → Gold), with Unity Catalog governance and Databricks Jobs orchestration.

| | |
|---|---|
| **Stack** | Databricks · PySpark · Delta Lake · Unity Catalog · Spark SQL |
| **Sources** | 6 CSV files across 2 disconnected systems — CRM and ERP |
| **Data Quality** | Encoding inconsistencies · corrupted prices · invalid dates · cross-source duplicate resolution |
| **Output** | Star schema: Dim_Customer · Dim_Product · Fact_Sales stored as Delta Tables |
| **Orchestration** | 3-task Job DAG · hard failure propagation · timestamped execution logging |

[View Repository](https://github.com/MoTahaAboHeiba/E-Commerce-Lakehouse-Using-Databricks)

---

### SQL Server Data Warehouse

Fully scriptable SQL Server warehouse implementing Bronze → Silver → Gold ETL layers via stored procedures, with dimensional modeling and pipeline observability.

| | |
|---|---|
| **Stack** | SQL Server · T-SQL · Stored Procedures · Star Schema |
| **Scale** | 60K+ records ingested across 6 sources |
| **Architecture** | 17 stored procedures orchestrated by 2 master procedures — any unit reruns independently |
| **Observability** | Per-step execution-time logging table for direct bottleneck identification |
| **Output** | Star schema exposed as SQL views for downstream analytics |

[View Repository](https://github.com/MoTahaAboHeiba/SQL-Data-Warehouse-project)

---

### EduMate-RAG — Production Retrieval API

Production RAG microservice with automated PDF ingestion, semantic retrieval with keyword-overlap reranking, and an offline evaluation harness across 73 QA pairs.

| | |
|---|---|
| **Stack** | FastAPI · LangChain · Qdrant Cloud · ChromaDB · Groq (Llama 3.3 70B) · HuggingFace Spaces |
| **Retrieval** | Semantic similarity + keyword-overlap reranking + deduplication over 24K+ indexed chunks |
| **Evaluation** | 73-query offline harness: 79.45% HitRate@5 · 81.4% Faithfulness |
| **Latency** | ~100ms ChromaDB local · ~240ms Qdrant Cloud production |
| **Deployment** | Decoupled microservice — platform-integrated and standalone modes |

[Live Demo](https://mo-taha-aboheiba-edumate-rag.hf.space) · [View Repository](https://github.com/MoTahaAboHeiba/EduMate-RAG)

---

### Online Retail Power BI Report

Transformed 541K raw retail transactions into a 3-page interactive dashboard covering revenue analysis, product performance, and data quality metrics.

| | |
|---|---|
| **Stack** | Power BI · Power Query · DAX |
| **ETL** | 541K → 406K records after cleaning; 8 engineered features |
| **Measures** | YoY growth · rolling averages · return rate via custom DAX |
| **Finding** | Top 25% of customers drive 65% of £9.73M revenue |
| **Extra** | Dedicated data quality page surfacing source anomalies |

[View Repository](https://github.com/MoTahaAboHeiba/Online-Retail-PowerBi-Report)

---

## Certifications

<div align="center">

| Certification | Issuer | Valid Until |
|:---|:---|:---|
| AWS Certified Cloud Practitioner (CLF-C02) | Amazon Web Services | May 2029 |
| HCIA Big Data Associate | Huawei Technologies | March 2029 |

</div>

---

## GitHub Stats

<div align="center">
  <img height="160" src="https://streak-stats.demolab.com?user=MoTahaAboHeiba&theme=tokyonight&hide_border=true"/>
</div>

---

<div align="center">
  <img src="https://raw.githubusercontent.com/MoTahaAboHeiba/MoTahaAboHeiba/main/dist/github-contribution-grid-snake-dark.svg" alt="snake animation" width="100%" />
</div>

---

<div align="center">

[Email](mailto:mohamed-aboheiba@outlook.com) · [LinkedIn](https://www.linkedin.com/in/mohamed-taha-abo-heiba/) · [Portfolio](https://motahaaboheiba.github.io) · [Resume](https://motahaaboheiba.github.io)

*Building data systems that are reliable by design, maintainable in practice, and useful to the business.*

</div>
