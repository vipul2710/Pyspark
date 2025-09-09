# PySpark Learning Scaffold 🚀

This repository contains my step-by-step PySpark learning journey, structured **topic by topic**.  
The goal is to go from **beginner → advanced**, building a strong foundation for real-world data engineering and analytics.

---

## 📂 Repo Structure

Pyspark/
│
├── notebooks/
│ ├── topic01_basics.ipynb # Setup & Basics (read, select, filter, withColumn, sort)
│ ├── topic02_aggregations.ipynb # Aggregations & GroupBy (count, sum, avg, multi-agg)
│ ├── topic03_joins.ipynb # Joins (inner, outer, broadcast)
│ ├── topic04_sql.ipynb # Spark SQL
│ ├── topic05_udfs.ipynb # UDFs & Pandas UDFs
│ ├── topic06_window.ipynb # Window functions
│ ├── topic07_performance.ipynb # Partitioning, caching, skew, broadcast joins
│ ├── topic08_etl_pipeline.ipynb # ETL pipeline (bronze → silver → gold)
│ ├── topic09_streaming.ipynb # Streaming basics
│ └── topic10_project.ipynb # Capstone project
│
└── README.md


---

## 📝 Topics Covered

- **Topic 1: Setup & Basics** ✅
  - SparkSession
  - Reading CSVs
  - `select`, `filter`, `withColumn`, `orderBy`

- **Topic 2: Aggregations & GroupBy** (in progress)
  - Count, sum, avg, min, max
  - Multi-aggregations
  - Group by one or more columns

- **Topic 3: Joins**
  - Inner/Outer joins
  - Semi/Anti joins
  - Broadcast joins

*(more topics to be added as I progress)*

---

## ⚡ How to Use

1. Clone this repo:
   ```bash
   git clone https://github.com/<your-username>/Pyspark.git

Open notebooks in Databricks Free Edition or any Jupyter environment with PySpark installed.

Run cells topic by topic.
