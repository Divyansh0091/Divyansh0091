<div align="center">

# Hi there, I'm Divyansh Soni 👋
### 🚀 Data Engineer & Cloud Architecture Enthusiast

*Building scalable, reliable, and production-grade data pipelines, modern data warehouses, and automated ETL/ELT workflows.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/divyansh-soni-data) 
[![GitHub](https://img.shields.io/badge/GitHub-Portfolio-black?style=flat&logo=github)](https://github.com/Divyansh0091)

</div>

---

### 🛠️ Enterprise Technical Stack

| Category | Technologies & Tools |
| :--- | :--- |
| **Cloud & Storage** | Snowflake Data Warehouse, AWS S3, AWS IAM, Object Storage |
| **Big Data & Distributed Computing** | Apache Spark, Apache Scala, PySpark |
| **Real-Time Streaming & Ingestion** | Apache Kafka, Scrapy (Web Scraping) |
| **Data Engineering & ETL** | Snowpark Python, SQL, Change Data Capture (Streams & Tasks), Star Schema, Dimensional Modeling |
| **Orchestration & Automation** | Apache Airflow, Snowflake Tasks, Incremental Loads, Idempotent Pipelines |
| **Containerization & DevOps** | Docker, Kubernetes |
| **Analytics & Visualization** | Streamlit in Snowflake (SiS), Python, Pandas, Polars |
| **Version Control & CI/CD** | Git, GitHub, Collaborative Workflow |

---

### 🚀 Featured Data Engineering Projects

#### 1. [Snowflake US Accidents ETL & Analytics Pipeline](https://github.com/Divyansh0091/snowflake-us-accidents-etl-pipeline)
* **Architecture:** End-to-end automated ELT pipeline processing over **7.7 million records** from raw landing to analytical consumption.
* **Ingestion & Storage:** Staged raw CSV datasets from an **AWS S3 bucket** into Snowflake landing tables (`RAW_US_ACCIDENTS`) using bulk copy (`COPY INTO`).
* **Data Cleansing & Modeling:** Implemented robust type casting (`TRY_CAST`, `TRY_TO_TIMESTAMP`) and structured a **Star Schema** with normalized dimension tables (`DIM_LOCATION`, `DIM_WEATHER`) and cryptographic surrogate keys (`MD5`).
* **Automation & CDC:** Built real-time incremental processing using Snowflake **Streams** and recurring **Tasks** to orchestrate seamless updates.
* **Consumption Layer:** Developed an interactive real-time analytics UI via **Streamlit in Snowflake (SiS)** using native Snowpark sessions (`get_active_session()`).

---

### 📊 Data Analytics & Exploratory Projects

- **[US Accidents Big Data EDA](https://github.com/Divyansh0091/US-Accidents-Big-Data-EDA-Polars)**: Performed high-performance exploratory data analysis on massive datasets utilizing optimized dataframes.
- **[Online Retail Revenue Analysis](https://github.com/Divyansh0091/Online-Retail-Revenue-Analysis)**: Developed comprehensive business intelligence dashboards and KPIs to track revenue streams and customer behavior.

---

#### 2. [Instacart End-to-End Data Pipeline](https://github.com/Divyansh0091)

- *Architecture & Tech Stack:* End-to-end event-driven and fault-tolerant ELT data pipeline built using Apache Airflow, Apache Kafka, PySpark, AWS S3, Docker, and Python.
- *Real-Time Ingestion & Streaming:* Built a robust Kafka producer-consumer architecture to simulate, ingest, and validate high-throughput market transaction events with 100% delivery guarantees.
- *Workflow Orchestration:* Deployed containerized *Apache Airflow* DAGs to orchestrate multi-stage sequential pipelines, handling automated retries, scheduling, and error boundaries.
- *Distributed Processing & Modeling:* Leveraged *PySpark* to clean raw events and transform relational data into a clean *Star Schema* (Fact & Dimension tables) with optimized Parquet partitioning.
- *Cloud Storage & Data Lake:* Securely ingested and stored structured analytical datasets directly into an *Amazon S3* Data Lake for downstream BI and analytics consumption.
- 
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Divyansh0091&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Divyansh0091&layout=compact&theme=tokyonight&hide_border=true" width="48%" />
</div>
