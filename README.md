# 💳 Credit Card Customer Analysis & Churn Prediction

## 📌 Problem Statement
This project aims to analyze customer behavior and predict churn using historical credit card usage data. Insights will support retention strategies and product improvements for my clients POS sysytem. Customer retention is critical. This project explores credit card usage data to identify patterns in customer behavior and predict the likelihood of churn. By understanding which customers are most at risk of leaving, businesses can take proactive measures to improve satisfaction, loyalty, and profitability.

---

## Dataset Overview

- **Source**: [Kaggle Dataset](https://www.kaggle.com/datasets/aryashah2k/credit-card-customer-data/data)
- **Size**: 10,000+ anonymized customer records
- **Features**: Demographics, credit usage, online/bank/call behavior

---

## Project Objectives

- Predict customer churn using classification models
- Identify top behavioral drivers of churn
- Segment users by behavior using clustering
- Deliver actionable insights and business recommendations

---

## Exploratory Data Analysis (EDA)

Key exploration steps:
- Distribution of churned vs. retained customers
- Correlation analysis of usage patterns
- Feature distributions: credit limits, call volume, visit types

Visuals available in the `/visuals/` directory.

---

## Churn Prediction Modeling

**Models Used**:  
- Logistic Regression  
- Random Forest  

**Evaluation Metrics**:
| Model             | Accuracy | Precision | Recall | AUC Score |
|------------------|----------|-----------|--------|-----------|
| Logistic Regression | 85%   | 82%       | 80%    | 0.89      |
| Random Forest       | 88%   | 85%       | 83%    | 0.92      |

**Key Drivers of Churn**:
- Low tenure
- Fewer transactions
- Lower credit engagement
- Certain card types and income segments

---

## Customer Segmentation (K-Means Clustering)

**Features Used**:
- `Avg_Credit_Limit`  
- `Total_Credit_Cards`  
- `Total_visits_bank`  
- `Total_visits_online`  
- `Total_calls_made`

**Technique**:  
- K-Means clustering with PCA for 2D visualization
-  Standardized inputs for modeling
-  
**PCA Cluster Visualization**  
The PCA plot below illustrates distinct groupings of customer behavior after applying K-Means clustering. Each cluster reflects unique engagement profiles, used to inform the personas outlined in the business strategy.

![PCA Clusters](visuals/pca.png)

**Identified Segments**:
1. **Dormant Users**  
   - Low activity across all channels  
   - Strategy: Onboarding nudges + reactivation incentives

2. **Digital Enthusiasts**  
   - High credit usage + online engagement  
   - Strategy: Reward loyalty, upsell premium features

3. **Support-Reliant Traditionalists**  
   - High call volume, low online use  
   - Strategy: Guide toward digital self-service + education

---

## Business Recommendations

| Customer Segment            | Recommendation                                |
|----------------------------|-----------------------------------------------|
| Dormant Users              | Re-engagement incentives, personalized outreach |
| Digital Enthusiasts        | Loyalty program, exclusive offers             |
| Support-Reliant Customers  | Chatbot tools, digital migration training     |

---

## Business Impact

- Increase retention by targeting churn-prone groups  
- Reduce support costs through digital self-service initiatives  
- Tailor marketing for higher engagement + ROI  
- Unlock strategic personas from raw behavior data

---

## Tools & Technologies

- Python, Pandas, NumPy, Seaborn, Scikit-learn, PCA, KMeans  
- Google Colab  
- Visualizations in Matplotlib & Seaborn

---

