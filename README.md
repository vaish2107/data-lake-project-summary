# AWS Data Lake Project – Master’s Capstone (Summary)

This repository summarizes a semester-long academic project where we designed and implemented a centralized data lake architecture using AWS services to improve cross-functional reporting and analytics for departments like Finance, PMO, and HR.

> ⚠️ *Note: Due to academic restrictions, the code is not shared. This repository includes architectural concepts, process documentation, and a visual overview of the solution.*

---

## 📌 Project Overview

**Use Case**:  
Organizations struggle to consolidate structured and unstructured data for effective decision-making. Our goal was to build a cost-effective, scalable cloud data lake to integrate diverse data formats and support analytics.

---

## 🛠 Architecture Summary

- **Storage**: AWS S3 (Staging Layer)
- **ETL & Transformation**: AWS Glue, Textract
- **Schema & Processing**: PostgreSQL (RDS)
- **Analytics Layer**: AWS Athena (Ad-hoc reporting)

---

## 🔁 ETL Process Highlights

| Layer          | Description                                                             |
|----------------|-------------------------------------------------------------------------|
| Staging Layer  | Temporary storage of incoming files (CSV, PNG, XLSX)                   |
| Transformation | Textract used to extract from image; data normalized using Glue jobs   |
| Merge Layer    | Consolidated into PostgreSQL using schema-based ingestion              |
| Reporting      | Athena used for SQL-based ad-hoc analysis and visualization            |

---

## 📊 Key Learnings

- Integrated structured and unstructured data using AWS services
- Built a layered lake architecture for queryable storage
- Managed GDPR-relevant data ingestion and separation
- Simulated real business queries using AWS Athena

---

## 🖼 Architecture Diagram

![image](https://github.com/user-attachments/assets/56f2a702-58b8-4bf8-95f6-8375be36ea9d)





