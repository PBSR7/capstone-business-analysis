# CAPSTONE BUSINESS ANALYSIS

## Overview

This project presents a complete end-to-end data analysis workflow to understand and reduce customer churn. The analysis identifies key factors influencing churn and provides actionable business recommendations using data-driven techniques.

---

## Objectives

- Analyze customer behavior patterns  
- Identify key drivers of churn  
- Perform exploratory data analysis (EDA)  
- Build a predictive model  
- Provide actionable business recommendations  

---

## Project Structure

capstone-business-analysis/
│
├── data/
│ ├── customer_churn.csv
│ ├── cleaned_data.csv
│
├── notebooks/
│ ├── 1_data_cleaning.ipynb
│ ├── 2_eda.ipynb
│ ├── 3_analysis.ipynb
│
├── reports/
│ ├── executive_summary.pdf
│ ├── technical_report.pdf
│
├── presentation/
│ ├── business_presentation.pptx
│
├── README.md
├── requirements.txt

---

## Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/pbsr7/capstone-business-analysis.git
cd capstone-business-analysis
2. Install dependencies
pip install -r requirements.txt
3. Run notebooks

Open Jupyter Notebook or VS Code and run:

1_data_cleaning.ipynb
2_eda.ipynb
3_analysis.ipynb
Dataset Information
Dataset: Customer Churn Dataset
Records: 500+
Features: Customer demographics and usage
Target Variable: Churn
Data Preprocessing
Removed missing values
Removed duplicate records
Standardized column names
Converted categorical variables
Saved cleaned dataset
Exploratory Data Analysis (EDA)
Churn distribution analysis
Correlation heatmap
Feature vs churn analysis (boxplots)
Distribution plots
Model Building
Model: Logistic Regression
Data Split: 80% training / 20% testing
Preprocessing: One-hot encoding
Evaluation Metrics:
Accuracy
Precision
Recall
F1 Score
Key Insights
Certain customer behaviors strongly influence churn
High-risk customer segments identified
Early-stage customers show higher churn tendency
Business Recommendations
Target high-risk customers with offers
Improve onboarding experience
Introduce retention programs
Monitor churn indicators continuously
Results
Model successfully predicts churn behavior
Provides actionable insights for business decisions
Limitations
Limited dataset size
Basic model used (Logistic Regression)
Limited feature engineering
Future Improvements
Use advanced models (Random Forest, XGBoost)
Handle class imbalance (SMOTE)
Deploy model using Flask or Streamlit
Build dashboard (Power BI / Tableau)
Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Conclusion

This project demonstrates how data analysis and machine learning can be used to understand customer churn and improve retention strategies. It highlights the importance of data-driven decision-making in business.

Acknowledgements
Dataset for educational purposes
Inspired by real-world business problems
