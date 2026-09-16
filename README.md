
# End-to-End Brazilian E-Commerce Analytics Platform

## Project Overview

This project presents a complete data engineering and machine learning solution built using the Brazilian Olist E-Commerce dataset.

The project combines:

* Automated ETL Pipeline
* PostgreSQL Data Warehouse
* Apache Airflow Orchestration
* Data Quality Validation
* Power BI Dashboards
* Exploratory Data Analysis
* Feature Engineering
* Machine Learning for Late Delivery Prediction

The system processes approximately 100,000 real e-commerce orders and transforms raw CSV files into analytics-ready datasets and predictive models.

---

## Architecture

Kaggle API → Python ETL → Data Cleaning → PostgreSQL (3NF) → Apache Airflow → Quality Checks → Power BI → Feature Engineering → Machine Learning → Delivery Risk Prediction

---

## Technologies Used

### Data Engineering

* Python
* Apache Airflow
* PostgreSQL
* SQLAlchemy
* Kaggle API
* WSL

### Data Analytics

* Pandas
* NumPy
* Matplotlib
* Seaborn

### Machine Learning

* Scikit-learn
* XGBoost
* SMOTE
* SciPy

### Business Intelligence

* Power BI

---

## Key Features

### Data Engineering

✔ Automated ETL Pipeline

✔ Apache Airflow DAG Scheduling

✔ PostgreSQL 3NF Database Design

✔ Foreign Key Validation

✔ Data Quality Checks

✔ Incremental Data Processing

---

### Analytics & Machine Learning

✔ Feature Engineering

✔ Class Imbalance Handling using SMOTE

✔ Comparison of 5 Machine Learning Models:

* Logistic Regression
* Decision Tree
* Random Forest
* KNN
* XGBoost

✔ 10-Fold Cross Validation

✔ Statistical Testing

✔ Threshold Optimization

---

## Key Findings

* Geography was the strongest predictor of delivery delays.
* XGBoost achieved the highest ROC-AUC (0.611).
* Logistic Regression achieved the best default F1 score.
* Order-level data alone provides limited predictive power.
* External logistics information can improve model performance.

---

## Business Impact

This solution can help e-commerce companies:

* Identify high-risk deliveries early
* Improve customer satisfaction
* Optimize logistics operations
* Support data-driven decisions

---

## Future Improvements

* Cloud Deployment (AWS/GCP)
* Docker & Kubernetes
* Real-time Streaming
* Seller Performance Features
* Weather and Carrier Data Integration

---

## Authors

* Sandra Raj Pattuvakkaran
* Renato Silva
* Sudarsh Mekkampurath Sajeev
