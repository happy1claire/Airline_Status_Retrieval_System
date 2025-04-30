# ✈️ Airline Status Retrieval System

This project implements a comprehensive **ETL pipeline** that automates the extraction, transformation, and loading of weather and flight data into a cloud-based analytics system. The goal is to power data-driven dashboards that support decision-making around flight delays and disruptions.

---

## 🧠 Project Summary

We designed and deployed a robust data engineering workflow on **Google Cloud Platform (GCP)**. The pipeline automates:

- **Data ingestion** from external APIs
- **Batch processing** using PySpark on Dataproc
- **Scheduling and orchestration** with Cloud Scheduler and Workflows
- **Data warehousing** in BigQuery for analysis and dashboarding

---

## 🔄 Key Components and Workflow

### ✅ 1. Data Ingestion
- Developed Python scripts to extract data from **flight and weather APIs**
- Loaded raw JSON/CSV data into **GCP Cloud Storage**

### ✅ 2. Batch Processing
- Created two **PySpark ETL scripts** to clean and transform the ingested data
- Deployed the jobs using **Google Cloud Dataproc**
- Used **Cloud Scheduler** and **Workflow templates** to trigger ETL jobs every 3 hours, ensuring up-to-date datasets

### ✅ 3. Data Integration & Analytics
- Transformed data was loaded into **Google BigQuery**
- Enabled real-time access to cleaned datasets for analytics and dashboarding

---

## 🛠️ Technologies Used

- **Google Cloud Platform**
  - Cloud Storage
  - Dataproc (with PySpark)
  - Cloud Scheduler
  - Workflows
  - BigQuery
- **Python** (API interaction and ingestion)
- **PySpark** (data transformation and cleaning)

---
