# 📊 Telecom Customer Churn Prediction

An end-to-end Machine Learning project that predicts customer churn and assigns customer-level churn risk scores to support proactive customer retention strategies.

---

## 📌 Project Overview

Customer churn is a major challenge in the telecom industry. Identifying customers who are likely to leave allows businesses to take proactive retention measures before the customer churns.

This project develops a machine learning pipeline to:

- Analyze customer behavior and characteristics.
- Identify factors associated with customer churn.
- Build and compare multiple classification models.
- Predict the probability of customer churn.
- Generate a `CHURN_FLAG` for high-risk customers.
- Segment customers into Low, Medium, and High churn-risk categories.
- Provide actionable business recommendations for customer retention.

---

## 🎯 Business Objectives

The project focuses on three primary objectives:

1. **Identify churn drivers**  
   Determine which customer characteristics and behavioral patterns are associated with churn.

2. **Predict churn probability**  
   Develop machine learning models capable of estimating the likelihood that a customer will churn.

3. **Enable proactive retention**  
   Convert model predictions into customer risk scores and `CHURN_FLAG` values that can be used to prioritize retention campaigns.

---

## 📂 Dataset

The dataset contains telecom customer-level information including demographic, geographic, financial, and usage-related attributes.

### Dataset Features

| Feature | Description |
|---|---|
| `customer_id` | Unique customer identifier |
| `telecom_partner` | Telecom service provider |
| `gender` | Customer gender |
| `age` | Customer age |
| `state` | Customer state |
| `city` | Customer city |
| `pincode` | Customer PIN code |
| `date_of_registration` | Customer registration date |
| `num_dependents` | Number of dependents |
| `estimated_salary` | Estimated customer salary |
| `calls_made` | Number of calls made |
| `sms_sent` | Number of SMS messages sent |
| `data_used` | Customer data usage |
| `churn` | Target variable: 0 = retained, 1 = churned |

### Target Variable

```text
churn = 0 → Customer retained
churn = 1 → Customer churned
