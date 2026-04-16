# SparkScale: Telecom Churn Prediction
A distributed Machine Learning pipeline built with Apache Spark and PySpark.

## 🚀 Project Overview
This project simulates a large-scale (2TB+) telecom environment to predict customer churn. 
It uses a 4-week distributed architecture:

* **Week 1:** Data Ingestion with strict Schema Validation.
* **Week 2:** Feature Engineering using Spark SQL and VectorAssembler.
* **Week 3:** Training a Distributed Random Forest Classifier (MLlib).
* **Week 4:** Model Persistence and Columnar Storage (Parquet).

## 🛠️ Tech Stack
* **Language:** Python
* **Engine:** Apache Spark (PySpark)
* **Environment:** Google Colab / Docker
* **Storage:** Apache Parquet
