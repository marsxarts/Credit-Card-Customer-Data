# 💳 Credit Card Customer Analysis & Churn Prediction

## 📌 Problem Statement
This project aims to analyze customer behavior and predict churn using historical credit card usage data. Insights will support retention strategies and product improvements for the POS sysytem. Customer retention is critical. This project explores credit card usage data to identify patterns in customer behavior and predict the likelihood of churn. By understanding which customers are most at risk of leaving, businesses can take proactive measures to improve satisfaction, loyalty, and profitability.

## Dataset
- **Source**: [Kaggle Dataset](https://www.kaggle.com/datasets/aryashah2k/credit-card-customer-data/data)
- **Records**: 10,000+ anonymized customer records
- **Features**: Credit score, age, income category, card category, months on book, transaction data, churn indicator

## Objectives
- Analyze and visualize key trends in customer behavior
- Predict churn using classification models
- Identify top drivers of churn and actionable insights
- Create clear visual summaries and stakeholder-ready recommendations

## Tools & Technologies
- **Python**: pandas, numpy, seaborn, matplotlib, scikit-learn
- **Notebook**: Jupyter

## Exploratory Analysis
- Distribution of churned vs. retained customers
- Relationship between tenure, transaction volume, and churn
- Correlation heatmaps for feature relationships

## Modeling
- Models: Logistic Regression, Random Forest, Gradient Boosting
- Evaluation Metrics: Accuracy, Precision, Recall, F1 Score, ROC AUC
- Feature Importance plots to explain model insights

## Key Findings
- Customers with lower tenure and fewer transactions are more likely to churn
- Income category and card type also influence churn behavior
- Targeted retention campaigns can focus on early-stage and low-engagement users

## Recommendations
- Onboard new users with higher engagement early in their journey
- Monitor low-spending users for early signs of disengagement
- Tailor offers and services based on churn risk segments

## Model Performance (sample)
| Model              | Accuracy | Precision | Recall | AUC Score |
|-------------------|----------|-----------|--------|-----------|
| Logistic Reg.      | 85%      | 82%       | 80%    | 0.89      |
| Random Forest      | 88%      | 85%       | 83%    | 0.92      |
