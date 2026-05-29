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

---

# 📊 Customer Segmentation Analysis

To better understand churn behavior patterns, segmentation analysis was performed based on:

* age group
* purchase frequency
* customer activity level

The objective of this analysis was to identify which customer segments showed higher churn risk and uncover potential behavioral indicators associated with customer retention.

---

## 👥 Churn Rate by Age Group

Customers aged **18–25** showed the highest churn rate compared to all other age groups.

Meanwhile, customers aged:

* 26–35
* 36–45
* 46–60

showed relatively lower and more stable churn rates.

<img width="159" height="168" alt="image" src="https://github.com/user-attachments/assets/d86884de-7093-4ff0-b345-031ce09fb01d" />

### Insight

Younger customers may:

* switch platforms more easily
* have lower brand loyalty
* respond more strongly to promotions and competitors

This suggests that younger customer segments may require stronger engagement and retention strategies.
<img width="531" height="374" alt="image" src="https://github.com/user-attachments/assets/c8bc902b-0f71-4d40-ac24-d4382fa7df39" />

---

## 🛒 Churn Rate by Purchase Frequency

Customers with **low purchase frequency** showed significantly higher churn rates compared to more active buyers.

Meanwhile:

* medium-frequency customers showed moderate churn
* high-frequency customers were generally more retained
<img width="215" height="171" alt="image" src="https://github.com/user-attachments/assets/183111d3-1fe5-4598-8757-fca0bb2b2564" />

### Insight

Lower purchasing activity appears strongly associated with customer churn.

Customers who purchase less frequently may:

* feel less connected to the platform
* have lower engagement levels
* lose interest more quickly over time

This suggests that purchase frequency may serve as an early warning signal for retention risk.
<img width="531" height="374" alt="image" src="https://github.com/user-attachments/assets/4ffc03a8-7567-49d5-b1f1-d593d0a26a4a" />


---

## 📉 Churn Rate by Customer Activity

Churn rate increased consistently as customer inactivity increased.

* Highly inactive customers showed the highest churn rate
* Very active customers showed the lowest churn rate
<img width="200" height="183" alt="image" src="https://github.com/user-attachments/assets/dc28adb7-01a9-4a03-b18d-c7bd5ea3c645" />

### Insight

Customer inactivity appears to be one of the strongest behavioral indicators of churn risk.

Long inactivity periods may indicate:

* declining customer engagement
* reduced platform interest
* weakening customer retention

This suggests that monitoring inactivity duration may help businesses identify at-risk customers earlier before complete churn occurs.
<img width="609" height="374" alt="image" src="https://github.com/user-attachments/assets/168393f2-89af-4798-83a0-592b45ba7619" />


---

# 🧠 Additional Learnings

Several important learnings emerged during this analysis:

* Customer churn is closely related to engagement behavior
* High-spending customers are not always the most loyal customers
* Activity level may be a stronger churn indicator than transaction value
* Segmentation analysis helps transform raw metrics into actionable business insights

---

# 🚀 Current Progress

✅ Data cleaning completed
✅ Missing values handled
✅ Exploratory Data Analysis completed
✅ Customer segmentation analysis completed
⬜ Dashboard development in Power BI
⬜ Business recommendation framework
⬜ Final project storytelling
⬜ Predictive churn modeling (optional)
