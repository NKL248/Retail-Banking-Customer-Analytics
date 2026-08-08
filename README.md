# Retail Banking Customer Analytics

## Overview

This project analyzes retail banking customer data to understand customer behavior, identify factors associated with churn, and predict customers who are more likely to leave.

The project uses PySpark and Spark SQL for data processing and analysis, followed by a Logistic Regression model for churn prediction.

## Objectives

- Analyze customer demographics and banking behavior
- Identify patterns associated with customer churn
- Compare customer behavior across different segments
- Build a machine learning model to predict churn
- Generate insights that can support customer retention strategies

## Dataset

The dataset contains 10,000 banking customer records with information related to:

- Credit score
- Geography
- Gender
- Age
- Tenure
- Account balance
- Number of products
- Credit card ownership
- Active membership
- Estimated salary
- Customer churn status

## Technologies Used

- Python
- PySpark
- Spark SQL
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Project Workflow

1. Data loading and exploration
2. Data cleaning
3. Exploratory data analysis
4. Customer segmentation analysis
5. Spark SQL analysis
6. Feature preparation
7. Logistic Regression
8. Model evaluation
9. Feature analysis
10. Business recommendations

## Analysis

The analysis explores:

- Customer distribution by geography and gender
- Age and balance distribution
- Churn across different customer groups
- Relationship between customer activity and churn
- Product usage patterns
- Factors influencing customer churn

## Machine Learning

A Logistic Regression model was developed to predict whether a customer is likely to churn.

### Model Results

- Accuracy: 80.6%
- AUC Score: 0.759

The model provides a baseline approach for identifying customers who may be at higher risk of leaving.

## Key Findings

- Customer age showed a noticeable relationship with churn.
- Active members were less likely to churn.
- Customer geography showed differences in churn behavior.
- Customer balance and product usage provided additional signals for churn analysis.

## Business Recommendations

- Identify high-risk customers for targeted retention campaigns.
- Encourage inactive customers to engage more with banking services.
- Use customer behavior to provide more relevant financial products.
- Use predictive analytics to prioritize retention efforts.
