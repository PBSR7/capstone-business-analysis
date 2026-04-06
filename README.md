# Customer Churn Analysis – Capstone Project

## Project Overview

This project focuses on analyzing customer churn using data-driven techniques. The goal is to identify key factors influencing customer churn and provide actionable business recommendations to improve customer retention.

---

## Objectives

* Analyze customer behavior and churn patterns
* Perform end-to-end data analysis
* Build a predictive model to identify churn risk
* Provide actionable business insights and recommendations

---

## Project Structure

```
capstone-business-analysis/
│
├── data/
│   ├── customer_churn.csv
│   ├── cleaned_data.csv
│
├── notebooks/
│   ├── 1_data_cleaning.ipynb
│   ├── 2_eda.ipynb
│   ├── 3_analysis.ipynb
│
├── reports/
│   ├── executive_summary.pdf
│   ├── technical_report.pdf
│
├── presentation/
│   ├── modern_canva_style_presentation.pptx
│
├── capstone_analysis.ipynb
├── README.md
├── requirements.txt
```

---

## Setup Instructions

### 1️.Clone the Repository

```bash
git clone https://github.com/your-username/capstone-business-analysis.git
cd capstone-business-analysis
```

### 2️.Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️.Run Jupyter Notebook

```bash
jupyter notebook
```

---

## Dataset Information

* Dataset: Customer Churn Data
* Rows: 500+
* Features: Customer attributes and usage data
* Target Variable: **Churn**

---

## Workflow

### 1. Data Cleaning

* Removed missing values
* Removed duplicates
* Standardized column names

### 2. Exploratory Data Analysis (EDA)

* Churn distribution analysis
* Correlation heatmap
* Feature vs churn visualization
* Distribution analysis

### 3. Model Building

* Algorithm: Logistic Regression
* Data split: 80% training / 20% testing
* Evaluation metrics: Accuracy, Precision, Recall

---

## Key Visualizations

* Churn distribution plot
* Correlation heatmap
* Boxplots (feature vs churn)
* Histograms for feature distribution

---

## Results

* Model successfully predicts churn behavior
* Identified key factors influencing churn
* Achieved reliable classification performance

---

## Key Insights

* High-risk customers are identifiable
* Customer behavior significantly impacts churn
* Early-stage customers are more likely to churn

---

## Business Recommendations

* Offer targeted discounts to high-risk customers
* Improve onboarding experience
* Implement customer retention programs
* Monitor churn indicators continuously

---

## Deliverables

* Jupyter Notebooks (Data Cleaning, EDA, Model)
* Presentation (Canva-style PPT)
* Executive Summary
* Technical Report
* Well-documented code repository

---

## Technologies Used

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Testing & Validation

* Verified cleaned dataset
* Evaluated model using test data
* Checked consistency of results

---

## Limitations

* Moderate dataset size
* Limited feature diversity
* Basic model used (Logistic Regression)

---

## Future Improvements

* Implement advanced ML models (Random Forest, XGBoost)
* Perform feature engineering
* Handle class imbalance
* Deploy model as a web application

---

## Conclusion

This project demonstrates an end-to-end data analysis workflow, from raw data to actionable insights. The findings highlight how data-driven strategies can effectively reduce customer churn and improve business performance.

---

## Acknowledgements

This project was completed as part of a capstone data analysis program.

---
