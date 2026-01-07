# 📊 Customer Churn Analysis using Python & Matplotlib

## 📌 Project Overview
Customer churn is one of the biggest challenges faced by subscription-based businesses.  
This project performs **Exploratory Data Analysis (EDA)** on a telecom customer dataset to identify **key factors that influence customer churn** and provide **business-driven insights** for improving customer retention.

---

## 🎯 Objectives
- Understand customer behavior and churn patterns
- Identify high-risk customer segments
- Analyze the impact of contracts, pricing, services, and billing on churn
- Visualize insights using Python and Matplotlib
- Provide actionable business recommendations

---

## 🗂 Dataset Description
The dataset contains customer demographic information, services subscribed, billing details, and churn status.

### Key Columns
| Column | Description |
|------|------------|
| customerID | Unique customer identifier |
| gender | Customer gender |
| SeniorCitizen | Whether the customer is a senior citizen |
| Partner | Whether the customer has a partner |
| Dependents | Whether the customer has dependents |
| tenure | Number of months the customer stayed |
| PhoneService | Whether the customer has phone service |
| InternetService | Type of internet service |
| OnlineSecurity | Online security add-on |
| TechSupport | Tech support add-on |
| StreamingTV | Streaming TV service |
| StreamingMovies | Streaming Movies service |
| Contract | Contract duration |
| MonthlyCharges | Monthly billing amount |
| TotalCharges | Total amount paid |
| PaymentMethod | Method of payment |
| Churn | Whether the customer churned |

---

## 🛠 Tools & Libraries Used
- Python  
- Pandas  
- Matplotlib  
- Jupyter Notebook / VS Code  

---

## 🔍 Analysis Performed

### 1️⃣ Churn Distribution
- Overall churn rate analysis
- Identifies imbalance between churned and retained customers

---

### 2️⃣ Customer Relationship Analysis
- Partner vs Churn  
- Dependents vs Churn  

**Insight:**  
Customers with partners and dependents churn less, indicating higher stability.

---

### 3️⃣ Tenure Analysis (Very Important)
- Tenure distribution using histogram
- Tenure vs Churn using boxplot

**Insight:**  
Most churn happens in the early months of customer lifecycle.

---

### 4️⃣ Contract Analysis (Top Churn Driver)
- Contract type distribution
- Contract vs Churn comparison

**Insight:**  
Month-to-month contracts have the highest churn, while two-year contracts are the most stable.

---

### 5️⃣ Service Usage Analysis
- InternetService vs Churn  
- OnlineSecurity vs Churn  
- TechSupport vs Churn  
- Streaming services vs Churn  

**Insight:**  
Customers without add-on services churn more. Add-ons increase customer retention.

---

### 6️⃣ Billing & Payment Analysis
- MonthlyCharges distribution
- MonthlyCharges vs Churn
- TotalCharges vs Churn
- PaymentMethod vs Churn

**Insight:**  
Higher monthly charges and electronic check payment methods are associated with higher churn.

---

## 📊 Visualizations Used
- Histogram
- Bar charts (using crosstab and groupby)
- Boxplots
- Violin plots
- Donut charts

---

## 🧠 Key Business Insights
- Churn occurs mostly in early tenure
- Month-to-month contracts are high risk
- Higher monthly charges increase churn
- Add-on services significantly reduce churn
- Auto-payment users are more loyal
- Senior citizens require targeted retention strategies

---

## 🚀 Business Recommendations
- Improve onboarding experience in the first 3–6 months
- Encourage long-term contracts through discounts
- Bundle add-on services to improve retention
- Offer special plans for high monthly charge customers
- Promote auto-payment options

---

## 🎤 Interview-Ready Summary
> “I performed exploratory data analysis using Python and Matplotlib to analyze customer churn patterns. I found that tenure, contract type, monthly charges, and add-on services are the strongest drivers of churn.”

---

## 📁 Project Structure
