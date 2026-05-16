# 📊 Customer Churn Analysis

## 📌 Project Overview

Customer retention is one of the biggest challenges in many industries, especially in e-commerce businesses where customers can easily switch to competitors.

This project analyzes customer churn behavior using an e-commerce customer dataset containing 50,000 customer records to identify behavioral patterns associated with churn and generate actionable business insights.

### Business Problem

> How can businesses identify customers who are at risk of churning before they stop engaging or making purchases?

By analyzing customer engagement, purchasing behavior, and interaction patterns, this project aims to help businesses better understand customer retention and potential churn indicators.

---

# 📂 Dataset Information

- **Dataset Type:** E-commerce Customer Behavior Dataset
- **Total Records:** 50,000 customers

### Features Include
- Customer demographics
- Purchase behavior
- Engagement metrics
- Session activity
- Customer service interactions
- Churn status
<img width="619" height="234" alt="image" src="https://github.com/user-attachments/assets/8507b352-a4a3-4aa5-b67c-8766785e5d22" />

---

# 🛠️ Tech Stack

| Tools | Purpose |
|---|---|
| Python (Google Colab) | Data cleaning & analysis |
| Pandas | Data manipulation |
| Matplotlib | Data visualization |
| Google Sheets | Initial data storage |
| Power BI | Dashboard visualization (upcoming) |

---

# 🧹 Data Cleaning

The dataset contained several missing values and inconsistent data types.

## Data Preparation Steps

- Removed unnecessary columns
- Converted object/string columns into numeric format
- Handled missing values using median imputation
- Performed basic data validation

## Missing Value Handling

Median imputation was used for numerical features because customer behavior data tends to contain skewed distributions and outliers.
<img width="382" height="689" alt="image" src="https://github.com/user-attachments/assets/96b00dec-8880-447f-a644-21e9bd66e775" />

---

# 📈 Exploratory Data Analysis

Customer behavior between churned and non-churned users was compared using grouped averages.

## Customer Churn Distribution

| Churn Status | Total Customers | Percentage |
|---|---:|---:|
| Non-Churn | 35,550 | 71.1% |
| Churn | 14,450 | 28.9% |

### Initial Observation

Nearly 3 out of 10 customers were identified as churned customers, indicating that customer retention may represent a significant business challenge.

---

# 📊 Customer Behavior Comparison

| Metric | Non-Churn | Churn |
|---|---:|---:|
| Age | 38.55 | 35.99 |
| Membership Years | 2.98 | 2.98 |
| Login Frequency | 12.64 | 9.12 |
| Session Duration Avg | 29.07 | 23.99 |
| Pages Per Session | 9.24 | 7.43 |
| Total Purchases | 13.89 | 11.78 |
| Days Since Last Purchase | 26.54 | 35.97 |
| Average Order Value | 114.81 | 130.60 |
| Customer Service Calls | 5.18 | 6.90 |
| Lifetime Value | 1446.81 | 1425.42 |
<img width="1176" height="590" alt="image" src="https://github.com/user-attachments/assets/c1e0a64c-8bc0-4a9c-b2a0-9ca0bc2c477e" />

---

# 💡 Initial Insights

## Lower engagement is associated with churn

Customers who churned generally:
- logged in less frequently
- spent less time on the platform
- interacted with fewer pages

This suggests that declining engagement may be an early churn indicator.

---

## Longer inactivity period may increase churn risk

Customers who churned showed a significantly longer period since their last purchase.

This may indicate that inactivity duration can be used as an early retention monitoring signal.

---

## High spending does not always indicate loyalty

Interestingly, churned customers showed slightly higher average order values compared to non-churned customers.

This suggests that high-value customers are not automatically loyal and that engagement may play an important role in retention.
