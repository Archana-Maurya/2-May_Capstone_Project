#2 May Capstone Project
#  Smart Retail Analytics Platform

###  Built using PySpark & Microsoft Fabric

---

## 👩‍💻 Author

**Archana Maurya**
B.Tech CSE (3rd Year)
super set id:-6430994

---

## 🎯 Project Objective

The goal of this project is to design and implement an end-to-end **Smart Retail Analytics Platform** that processes large-scale retail data using distributed systems and provides actionable insights through interactive dashboards.

---

## 🧩 Business Scenario

RetailX operates across multiple cities and generates high volumes of transactional data daily.
This project enables:

* Efficient distributed data processing
* Centralized storage using Lakehouse architecture
* Real-time analytics capability
* Business intelligence through dashboards

---

## 🏗️ Architecture Overview

```
Raw Data (CSV)
     ↓
Bronze Layer (OneLake - Raw Files)
     ↓
Silver Layer (Cleaned Data - PySpark)
     ↓
Gold Layer (Aggregated Data)
     ↓
Power BI Dashboard (Insights)
```

---

## ⚙️ Technologies Used

* Apache Spark (PySpark)
* Microsoft Fabric (Lakehouse, OneLake)
* Spark SQL
* Power BI
* DAX

---

## 🔄 Data Pipeline Workflow

1. Data ingestion into Lakehouse (Bronze layer)
2. Data cleaning and transformation using PySpark (Silver layer)
3. Aggregation and business logic implementation (Gold layer)
4. SQL-based analysis
5. Visualization using Power BI

---

## 📊 Key Features

✔ Distributed data processing using PySpark
✔ Implementation of Bronze, Silver, Gold architecture
✔ RDD and DataFrame transformations
✔ SQL-based analytics
✔ Real-time streaming (conceptual implementation)
✔ Interactive Power BI dashboards

---

## 📈 Key Insights

* Certain product categories generate the highest revenue
* Metro cities contribute significantly to total sales
* Customer segmentation impacts purchasing behavior
* Sales trends vary across time periods

---

## 📌 DAX Measures

* **Total Sales** = SUM(price × quantity)
* **Average Order Value**
* **Sales Growth %** (Month-over-Month)

---

## 🔐 Security Considerations

* Sensitive data handling without exposure
* Role-based access via Microsoft Fabric
* Data validation to ensure integrity

---

## 🧠 Methodology

* Data ingestion → Processing → Storage → Analysis → Visualization
* Distributed computing used for scalability
* Structured data modeling applied

---

## ⚠️ Challenges Faced

* Handling large-scale data efficiently
* Managing compute limitations in Fabric
* Ensuring schema consistency

---

## 🚀 Project Highlights

* End-to-end data engineering pipeline
* Scalable Lakehouse architecture
* Business-focused analytics
* Industry-relevant implementation

---

## 📊 Final Outcome

A fully functional analytics platform capable of transforming raw retail data into meaningful business insights.

---

## 📎 Dataset Source

GitHub Dataset Repository:
https://github.com/himanshusar123/Datasets

---

## 🎯 Conclusion

This project demonstrates how modern data engineering tools like PySpark and Microsoft Fabric can be used to build scalable and efficient analytics systems for real-world business scenarios.

---
