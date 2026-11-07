# 🧠 Clinical Migraine Data Science & Machine Learning Pipeline

## 📌 Project Overview
This repository contains an end-to-end data science and machine learning project analysing a clinical migraine dataset ($N = 400$). The project bridges the gap between raw data engineering and real-world clinical interpretation, moving from SQL-based data aggregation to advanced supervised classification.

---

## 🚀 Key Features & Pipeline Steps
1. **Data Engineering & SQL Integration:** Loaded raw CSV records into an in-memory SQLite database to practice relational querying, null-value audits, and boundary checks.
2. **Exploratory Data Analysis (EDA):** 
   - Univariate analysis highlighting demographic peaks (migraine prevalence heavily concentrates between ages 20 and 40).
   - Bivariate correlation analysis proving feature independence (numerical attributes show near-zero linear correlation, reflecting the complex, non-linear nature of neurological pain).
3. **Machine Learning Modelling:**
   - Implemented multi-class classification using **Random Forest** and **XGBoost** to predict specific migraine types based on patient attributes and symptoms.
   - Evaluated model performance using classification reports and confusion matrix heatmaps.

---

## 🛠️ Tech Stack & Tools
* **Languages & Scripting:** Python, SQL
* **Data Science Libraries:** Pandas, NumPy, Scikit-Learn, XGBoost
* **Data Visualization:** Matplotlib, Seaborn
* **Database & Environment:** SQLite, Jupyter Notebook / Kaggle

---

## 📊 Analytical Findings & Insights

### 1. Data Integrity and Quality
* **Zero Missing Values:** An exhaustive null check across all columns confirmed a completely pristine dataset with no missing rows or anomalous entries.
* **Clean Ranges:** Verification of minimum and maximum boundaries showed realistic clinical ranges for patient age, attack duration, and pain intensity.

### 2. Demographic Trends & The "Prime Years" Peak
* **Age Concentration:** Distribution analysis reveals that migraine prevalence peaks sharply between ages 20 and 40, corresponding with high-stress professional and active life stages.
* **Natural Decline:** As patients enter later decades, reported cases drop significantly, mirroring real-world epidemiological trends where physiological changes reduce severity.

### 3. Clinical Presentation & Healthcare-Seeking Behaviour
* **Dominance of Auras:** *Typical aura with migraine* heavily outnumbers other categories in frequency counts.
* **Sampling Insight:** This distribution highlights a classic clinical sampling bias: patients experiencing disruptive sensory warnings (visual flashes, blind spots) are far more likely to seek specialised neurological care and documentation than those with milder symptoms.

### 4. Feature Independence & Non-Linear Complexity
* **Low Linear Correlation:** The correlation matrix showed that numerical features (Age, Duration, Frequency, and Intensity) have coefficients close to zero (maximum magnitude $\approx 0.15$).
* **Clinical Complexity:** This proves that pain intensity or attack duration does not scale linearly with age or frequency, reflecting the multi-factor nature of neurological pain.

---

## 📈 Model Performance
* Achieved an overall **92.5% test accuracy** using gradient boosting classifiers.
* Mapped out the predictive capabilities and limitations of imbalanced medical datasets across rare migraine sub-types (e.g., Hemiplegic Migraines).

---
📬 **Author:** Ananyaja Debadipta  
*Independent Data Analysis Researcher & Technical Writer*
