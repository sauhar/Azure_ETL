# 🚀 Real-World Azure Data Engineering Project

This end-to-end project follows a **layered architecture (Bronze → Silver → Gold)** and seamlessly integrates **Azure Data Factory**, **Databricks**, **Synapse Analytics**, **Delta Lake**, and **Power BI** into a unified data workflow. 💡

---

## 🔧 What I Built

### 📌 Azure Data Factory Pipelines

- **GitHub to Azure Data Lake**  
  Designed a dynamic pipeline that fetches files from a GitHub repository using a parameterized HTTP URL.

- **Raw to Silver Ingestion**  
  Ingests only the required file from Azure Data Lake Storage (ADLS) into the curated Silver layer, improving efficiency and modularity.

### 🔄 Data Transformation – Azure Databricks + PySpark (Silver Layer)

- Cleaned, filtered, and transformed raw data using **PySpark**.  
- Access management handled securely via **Microsoft Entra ID**.

### 📊 Data Serving – Azure Synapse Analytics (Gold Layer)

- Created external tables and views using **`OPENROWSET`** for optimized querying and data access.  
- Connected **Azure Synapse Analytics** with **Power BI** using **IAM-based access control**, enabling real-time, interactive dashboards.

---

## 🌟 What I Gained

- ✅ Hands-on expertise in **cloud-native ETL pipelines** using Azure tools  
- ✅ Built and optimized **scalable, modular data architecture**  
- ✅ Developed **efficient incremental pipelines** for batch processing  
- ✅ Applied **query optimization techniques** using **Delta Lake** and **Azure Synapse**

---

## 🔗 Project Links

- **GitHub Repo:** [Azure_ETL](https://github.com/sauhar/Azure_ETL)  
- **More Projects on PySpark:** [Databricks_PySpark](https://github.com/sauhar/Databricks_PySpark)

---

## 🧰 Tech Stack

`Azure Data Factory` | `Azure Data Lake Gen2` | `Azure Databricks` | `PySpark` | `Delta Lake` | `Synapse Analytics` | `Power BI`
