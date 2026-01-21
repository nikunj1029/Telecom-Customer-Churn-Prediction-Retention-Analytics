# Telecom-Customer-Churn-Prediction-Retention-Analytics
Built an end-to-end customer churn prediction system using a dataset of 348K+ telecom customers
This project focuses on analyzing customer behavior and predicting churn in a telecom business using data analysis, statistical techniques, and basic machine learning.
The goal is to identify key factors driving churn and help the business design targeted retention strategies instead of generic mass offers.

Business Problem

Telecom companies face high customer churn, which directly impacts revenue, customer lifetime value, and operational costs.
Key challenges:
Identifying which customers are likely to churn
Understanding why customers churn
Avoiding blanket discounts and instead applying data-driven retention actions

Exploratory Data Analysis (EDA)
Key Analysis Performed:
Distribution analysis of monthly charges
Comparison of customer support calls vs churn
Billing stress impact on churn
Usage level vs churn
Correlation analysis between numerical variables

Key Insights:
Customers with high billing stress and frequent support calls show higher churn
Low usage customers are more likely to churn
Monthly charges alone do not strongly explain churn without behavioral context

Statistical Analysis

Used descriptive statistics and distribution analysis to understand data behavior:
Mean, median, range for numerical features
Density plots to understand charge distribution
Correlation heatmap for numerical relationships


Feature Engineering
Created meaningful business-driven features:
Usage levels (low / medium / high)
Billing stress categories
Engagement levels
Risk indicators
Age group buckets

Encoding & Transformation
Applied one-hot encoding for categorical variables (region, contract type, payment method, engagement levels, risk levels)
Converted boolean columns to integer format
Selected only ML-relevant features for modeling

Machine Learning Model
Model Used:
Logistic Regression (Supervised Classification)
Why Logistic Regression?
Suitable for binary classification (churn / no churn)
Easy to interpret for business stakeholders

Business Outcome
Enabled identification of high-risk churn segments
Helped shift strategy from mass discounts to targeted retention
Provided explainable insights for marketing and customer success teams
Supported data-driven decisions on contract design and engagement programs

Tools & Skills Used
Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
Statistics & EDA
Supervised Machine Learning
