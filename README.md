# 🧠 Clinical Migraine Data Science & Machine Learning Pipeline

## 📌 Project Overview
This repository contains an end-to-end data science and machine learning project analysing a clinical migraine dataset ($N = 400$). The project bridges the gap between raw data engineering and real-world clinical interpretation, moving from SQL-based data aggregation to advanced supervised classification using XGBoost.

## 🚀 Key Features & Pipeline Steps
1. **Data Engineering & SQL Integration:** Loaded raw CSV records into an in-memory SQLite database to practice relational querying, null-value audits, and boundary checks.
2. **Exploratory Data Analysis (EDA):** 
   - Univariate analysis highlighting demographic peaks (migraine prevalence heavily concentrates between ages 20 and 40).
   - Bivariate correlation analysis proving feature independence (numerical attributes show near-zero linear correlation, reflecting the complex, non-linear nature of neurological pain).
3. **Machine Learning Modelling:**
   - Implemented multi-class classification using **Random Forest** and **XGBoost** to predict specific migraine types based on patient attributes and symptoms.
   - Evaluated model performance using classification reports and confusion matrix heatmaps.

## 🛠️ Tech Stack
* **Python** (Pandas, NumPy, Scikit-Learn, XGBoost)
* **SQL / SQLite** (Data extraction and aggregation)
* **Data Visualization** (Matplotlib, Seaborn)
* **Environment:** Jupyter Notebook / Kaggle

## 📊 Results & Performance
* Achieved an overall **93% accuracy** using gradient boosting.
* Mapped out the predictive capabilities and limitations of imbalanced medical datasets across rare migraine sub-types (e.g., Hemiplegic Migraines).
