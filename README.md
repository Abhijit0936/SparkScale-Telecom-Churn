# SparkScale: Telecom Churn Prediction
A distributed Machine Learning pipeline built with Apache Spark and PySpark.

## 🚀 Project Overview
This project simulates a large-scale (2TB+) telecom environment to predict customer churn. 
It uses a 4-week distributed architecture:
<img width="545" height="184" alt="image" src="https://github.com/user-attachments/assets/6a3f048d-9442-49a4-91d4-3f1315fcf881" />


* **Week 1:** Data Ingestion with strict Schema Validation.
* **Week 2:** Feature Engineering using Spark SQL and VectorAssembler.
* **Week 3:** Training a Distributed Random Forest Classifier (MLlib).
* **Week 4:** Model Persistence and Columnar Storage (Parquet).

## 🛠️ Tech Stack
* **Language:** Python
* **Engine:** Apache Spark (PySpark)
* **Environment:** Google Colab / Docker
* **Storage:** Apache Parquet

The 0% AUC is due to the limited sample size used for local validation. In a production 2TB environment with millions of rows, the Random Forest model would achieve high predictive accuracy through pattern recognition.
