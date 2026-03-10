# 📊 Healthcare Analytics: Predicting Hospital Readmissions for Diabetes Patients

## 📊 Project Overview

This project presents an **end-to-end healthcare analytics workflow** aimed at predicting **30-day hospital readmissions for diabetes patients** using machine learning techniques.

Hospital readmissions are a major challenge for healthcare systems because they increase **treatment costs, hospital workload, and patient risk**. By analyzing patient medical records and hospital visit history, this project builds predictive models to identify **patients at high risk of readmission**, allowing healthcare providers to intervene early and improve patient outcomes.

This project demonstrates a complete **data analytics pipeline**, including:

* Data acquisition
* Data preprocessing and cleaning
* Exploratory data analysis (EDA)
* Machine learning model development
* Model evaluation and interpretation
* Business insights and healthcare recommendations

---

# 🎯 Business Objectives

1. **Predict Hospital Readmissions** – Identify patients likely to be readmitted within 30 days
2. **Improve Patient Outcomes** – Help healthcare providers take preventive action
3. **Reduce Healthcare Costs** – Reduce avoidable hospital readmissions
4. **Support Data-Driven Healthcare Decisions** – Provide insights for hospital management

---

# 💡 Key Results

* 📊 Built predictive models to estimate **30-day readmission risk**
* 🤖 Compared **Logistic Regression and Random Forest models**
* 🔍 Identified key **patient features influencing readmission**
* 📈 Generated multiple **visualizations for healthcare insights**
* 🏥 Provided **data-driven recommendations** for hospital decision making

---

# 📁 Project Structure

```
healthcare-readmission-prediction/
│
├── diabetic_data.csv                # Raw dataset (download separately)
├── diabetic_data_cleaned.csv        # Cleaned & preprocessed dataset
├── healthcare_analytics.py          # Main analysis script
│
├── EXECUTIVE_SUMMARY.txt            # Executive summary report
├── README.md                        # Project documentation
│
├── visualizations/                  # All generated visualizations
│   ├── 01_target_distribution.png
│   ├── 02_numeric_distributions.png
│   ├── 03_categorical_distributions.png
│   ├── 04_numeric_vs_readmission.png
│   ├── 05_categorical_vs_readmission.png
│   ├── 06_correlation_matrix.png
│   ├── 07_model_comparison.png
│   ├── 08_confusion_matrices.png
│   ├── 09_feature_importance.png
│   ├── 10_probability_distribution.png
│   ├── 11_risk_stratification.png
│   └── 12_FINAL_DASHBOARD.png
│
└── requirements.txt                 # Python dependencies
```

---

# 🔬 Analytics Techniques Implemented

## Data Preprocessing

* Handling missing values
* Removing redundant columns
* Feature engineering
* Encoding categorical variables
* Data transformation

## Exploratory Data Analysis (EDA)

* Univariate analysis of patient attributes
* Bivariate analysis with readmission outcome
* Correlation analysis
* Distribution analysis of medical features
* Visualization of patient characteristics

---

# 🤖 Machine Learning Models

### Logistic Regression

* Baseline classification model
* Interpretable healthcare predictions

### Random Forest

* Ensemble machine learning algorithm
* Captures complex relationships between variables
* Provides **feature importance insights**

---

# 📊 Model Evaluation

The models were evaluated using:

* Train-test split
* Accuracy score
* Confusion matrix
* Model comparison analysis
* Prediction probability distribution

---

# 📊 Key Visualizations

The project includes several visualizations to understand healthcare patterns:

### Target Distribution

Shows distribution of patients who were readmitted vs not readmitted.

### Numeric Feature Distributions

Distribution of medical measurements and patient indicators.

### Categorical Feature Analysis

Exploration of patient demographics and hospital attributes.

### Correlation Matrix

Identifies relationships between important healthcare variables.

### Model Performance

Comparison of machine learning models.

### Final Dashboard

A comprehensive dashboard summarizing:

* Key insights
* Model results
* Patient risk distribution

---

# 🎓 Learning Outcomes

## Technical Skills

* Data cleaning and preprocessing
* Exploratory data analysis (EDA)
* Machine learning model development
* Model evaluation and comparison
* Data visualization using Python

## Business & Healthcare Skills

* Healthcare data interpretation
* Predictive analytics for hospitals
* Risk prediction modeling
* Translating analytics results into business insights

---

# 📈 Key Findings & Insights

### Patient Risk Patterns

Patients with **frequent hospital visits and complex medical histories** tend to have a higher probability of readmission.

### Feature Importance

Important predictors of readmission include:

* Number of previous hospital visits
* Patient age group
* Medical test results
* Treatment history

### Model Performance

Two machine learning models were evaluated:

**Logistic Regression**

* Simple and interpretable baseline model

**Random Forest**

* Higher predictive power
* Captures complex patterns in healthcare data

---

# 🔍 Methodology

## 1️⃣ Data Acquisition

Dataset used:

**Diabetes 130-US Hospitals Dataset (1999-2008)**
Source: **UCI Machine Learning Repository**

The dataset contains:

* Patient demographics
* Hospital admission records
* Medical test results
* Treatment information
* Readmission outcomes

---

## 2️⃣ Data Cleaning

Key preprocessing steps:

* Handling missing values
* Removing redundant variables
* Encoding categorical variables
* Creating binary readmission target variable

---

## 3️⃣ Exploratory Data Analysis

EDA helped to:

* Identify patterns in patient data
* Understand relationships between features
* Discover insights related to hospital readmissions

---

## 4️⃣ Model Development

Steps performed:

1. Feature selection
2. Train-test split
3. Model training
4. Model evaluation
5. Feature importance analysis

---

# 💻 Example Code

### Logistic Regression

```python
from sklearn.linear_model import LogisticRegression

model = LogisticRegression()
model.fit(X_train, y_train)

predictions = model.predict(X_test)
```

### Random Forest

```python
from sklearn.ensemble import RandomForestClassifier

rf = RandomForestClassifier(n_estimators=100)

rf.fit(X_train, y_train)

predictions = rf.predict(X_test)
```

---

# 📦 Dependencies

```
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
statsmodels
scipy
```

---

# 🎯 Use Cases

This project framework can be adapted for:

* Hospital readmission prediction
* Patient risk assessment
* Healthcare cost reduction strategies
* Predictive healthcare analytics
* Clinical decision support systems

---

# 🚀 Future Improvements

* Implement **XGBoost / LightGBM models**
* Build **interactive dashboards (Streamlit / Power BI)**
* Deploy prediction model using **Flask API**
* Add **SHAP model explainability**
* Develop **real-time healthcare prediction systems**

---

# 👨‍💻 Author

**Anurajsinh Vagehla**

Aspiring **Data Analyst / Business Analyst**
Interested in **Healthcare, with a focus on Machine Learning and Data Visualization.**

---
