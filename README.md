📌 Project Overview

This project demonstrates a complete end-to-end Data Engineering pipeline built using modern Azure data technologies. It simulates real-world enterprise scenarios, covering data ingestion, transformation,
governance, and analytics using best practices such as Medallion Architecture, Delta Lake, and Dimensional Modeling.
The pipeline ingests raw data from source systems, processes it through multiple transformation layers using Apache Spark (PySpark), and stores it in Delta Lake following the Medallion Architecture (Bronze, Silver,
Gold). The final curated datasets are modeled using Dimensional Data Modeling techniques and are optimized for analytical workloads and business intelligence consumption.This project closely mirrors real-world 
data engineering challenges such as incremental data ingestion, data quality enforcement, schema evolution, slowly changing dimensions (SCDs), and enterprise-level data governance using Unity Catalog.
![image alt](https://github.com/Charvi-M-J/Production-Ready-Azure-Data-Engineering-Project/blob/master/screenshot/Screenshot%202026-01-13%20180332.png?raw=true)
🧰 Technologies Used
🔹Microsoft Fabric
🔹Fabric Lakehouse
🔹Fabric Data Factory (Pipelines)
🔹Fabric Notebooks
🔹Apache Spark (PySpark)
🔹Delta Lake & Delta Tables
🔹Unity Catalog (Fabric Governance)
🔹Dimensional Data Modeling
🔹Slowly Changing Dimensions

📂 Project Structure
fabric-project/
│
├── RawData/
│   ├── SalesData.csv
│   └── IncrementalSales.csv
│
├── BronzeLayer/
│   └── bronze_ingestion_notebook.ipynb
│
├── SilverLayer/
│   └── silver_transformation_notebook.ipynb
│
├── GoldLayer/
│   └── gold_dim_fact_notebook.ipynb
│
├── Pipelines/
   └── fabric_data_pipeline

🎯 Key Learnings
✅ End-to-end Azure data pipeline
✅ Delta Lake & Delta Tables
✅ Unity Catalog for governance
✅ Slowly Changing Dimensions (SCD Type 1 & Type 2)
✅ Dimensional Data Modeling
✅ Medallion architecture


