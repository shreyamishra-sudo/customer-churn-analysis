## Project Overview

This project predicts customer churn using machine learning techniques and provides business insights to improve customer retention strategies.

The workflow includes data cleaning, feature engineering, exploratory data analysis (EDA), predictive modeling, and feature importance analysis to identify key churn drivers.

## Project Workflow

1. Data Cleaning  
   - Converted TotalCharges to numeric  
   - Handled missing values  
   - Encoded churn variable  

2. Feature Engineering  
   - Created tenure groups  
   - Calculated total services used  
   - Generated monthly charge categories  
   - Computed average monthly spend  

3. Exploratory Data Analysis (EDA)  
   - Analyzed churn distribution  
   - Identified high-risk customer segments  
   - Studied impact of contract type, tenure, and payment methods  

4. Model Preparation  
   - Encoded categorical variables  
   - Generated correlation heatmap  
   - Created model-ready dataset  

5. Machine Learning Models  
   - Logistic Regression  
   - Decision Tree (Tuned)  
   - Random Forest (Tuned)  

6. Feature Importance Analysis  
   - Identified key churn drivers  
   - Ranked most influential customer attributes  

## Model Performance Comparison

| Model | Accuracy | Recall (Churn) | Precision (Churn) |
|------|----------|----------------|-------------------|
| Logistic Regression | 0.791 | 0.49 | 0.64 |
| Decision Tree (Tuned) | 0.775 | 0.59 | 0.58 |
| Random Forest (Tuned) | 0.797 | 0.49 | 0.66 |

**Best Model:** Decision Tree (Tuned) — highest recall for churn detection.

## Key Business Insights

- Customers with shorter tenure show the highest churn rates.
- Higher monthly charges increase the likelihood of churn.
- Month-to-month contracts have significantly higher churn rates.
- Customers using fewer services are more likely to leave.
- Electronic payment users show higher churn risk.

These insights can help businesses design targeted retention strategies.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- PostgreSQL
- Power BI (Dashboard Visualization)
- Git & GitHub

## Project Structure

customer-churn-analytics/

├── data/
│   ├── raw/
│   ├── cleaned/
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_feature_engineering.ipynb
│   ├── 03_eda.ipynb
│   ├── 04_model_preparation.ipynb
│   ├── 05_model_training.ipynb
│   ├── 06_business_insights.ipynb
│
├── models/
├── reports/
├── dashboard/
├── README.md
