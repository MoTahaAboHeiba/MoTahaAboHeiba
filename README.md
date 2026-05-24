<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=700&size=28&duration=3000&pause=1000&color=38C2BF&center=true&vCenter=true&width=750&lines=Mohamed+Taha+Abo+Heiba;Data+Engineer;Spark+%7C+Databricks+%7C+Delta+Lake+%7C+AWS;Building+Scalable+Data+Pipelines" />

<a href="mailto:mohamed-aboheiba@outlook.com"><img src="https://img.shields.io/badge/Email-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/mohamed-taha-abo-heiba/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://motahaaboheiba.github.io"><img src="https://img.shields.io/badge/Portfolio-111827?style=for-the-badge&logo=github&logoColor=white"/></a>

<img src="https://komarev.com/ghpvc/?username=MoTahaAboHeiba&label=Profile+Views&color=38C2BF&style=flat" />

</div>

---

## Current Focus

- Production-grade ETL pipelines on Databricks and Delta Lake
- Cloud-native data platforms on AWS — Glue, Redshift, EMR, Athena
- Data Warehousing and Medallion Architecture
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
| **Architecture** | Medallion layers implemented as isolated, rerunnable stored procedures |
| **Observability** | Execution log table tracking run timestamps and row counts per layer |
| **Output** | Star schema optimized for analytical queries |

[View Repository](https://github.com/MoTahaAboHeiba/SQL-Data-Warehouse-project)

---

### Document Indexing & Retrieval Pipeline (RAG)

Production RAG API with automated PDF ingestion, semantic chunking, vector indexing, and conversational memory. Sub-100ms query responses against indexed documents.

| | |
|---|---|
| **Stack** | FastAPI · LangChain · ChromaDB · Groq (Llama 3.3 70B) |
| **Accuracy** | 100% source-grounded — responses scoped strictly to indexed content |
| **Pipeline** | Automated PDF chunking → embedding → vector store ingestion |
| **API** | REST interface with persistent conversational memory across sessions |

[View Repository](https://github.com/MoTahaAboHeiba/EduMate-RAG)

---

### Online Retail Power BI Report

Transformed 541K raw retail transactions into a 3-page interactive dashboard covering sales trends, product performance, and data quality metrics.

| | |
|---|---|
| **Stack** | Power BI · Power Query · DAX |
| **ETL** | Full transformation pipeline built in Power Query before report layer |
| **Measures** | YoY growth · rolling averages · return rate via custom DAX |
| **Extra** | Dedicated data quality page surfacing source anomalies |

[View Repository](https://github.com/MoTahaAboHeiba/Online-Retail-PowerBi-Report)

---

## Certifications

<div align="center">

| Certification | Issuer |
|:---|:---|
| AWS Certified Cloud Practitioner (CLF-C02) | Amazon Web Services |
| HCIA — Big Data Associate | Huawei |

</div>

---

## GitHub Stats

<div align="center">
  <img height="160" src="https://streak-stats.demolab.com?user=MoTahaAboHeiba&theme=tokyonight&hide_border=true" />
  &nbsp;&nbsp;
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MoTahaAboHeiba&layout=compact&theme=tokyonight&hide_border=true" />
</div>

---

<div align="center">

[Email](mailto:mohamed-aboheiba@outlook.com) · [LinkedIn](https://www.linkedin.com/in/mohamed-taha-abo-heiba/) · [Portfolio](https://motahaaboheiba.github.io)

*Building scalable data platforms and distributed data systems.*

</div>
