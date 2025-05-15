# 💳 Credit Card Spend Analysis & Risk Profiling

This project focuses on analyzing credit card usage data to extract key insights, identify risk segments, and calculate profitability for a bank. It involves extensive **data preprocessing**, **sanity checks**, **feature engineering**, **monthly aggregations**, and **insightful visualizations**. Additionally, it includes **interest rate computation** and **segment-wise profitability**.

---

## 📁 Dataset Description

The project uses three CSV datasets:
- `customer.csv` – Contains customer demographic information.
- `spend.csv` – Records of monthly customer spending by category.
- `repayment.csv` – Repayment amounts by customers for each month.

---

## ✅ Objectives

1. Perform data cleaning and sanity checks.
2. Aggregate monthly spending and repayment.
3. Identify high-value customers.
4. Segment analysis based on spend and profit.
5. Apply interest rate logic for overdue payments.
6. Visualize key insights using univariate and bivariate plots.

---

## 🛠️ Tasks Performed

### 🔹 Data Cleaning & Preprocessing
- Converted `month` column to datetime.
- Removed ages below 18 or handled them meaningfully.
- Identified customers exceeding credit limits.
- Filled missing values with appropriate logic.

### 🔹 Monthly Calculations
- Calculated monthly spend and repayment per customer.
- Created summary tables using `groupby`.

### 🔹 Business Questions Answered
1. **Monthly spend of each customer**
2. **Monthly repayment of each customer**
3. **Top 10 customers by repayment**
4. **Segment spending analysis**
5. **Age group spending analysis**
6. **Most profitable segment**
7. **Top spending categories**
8. **Interest applied (2.9%) to due amounts**
9. **Monthly bank profit**

---

## 📊 Exploratory Data Analysis

### Univariate Analysis
- Age Distribution
- Gender Distribution
- Customer Segments
- Spending Categories

### Bivariate Analysis
- Age vs Monthly Spend
- Segment vs Monthly Spend

### Multivariate Analysis
1. Monthly spend of each customer
2. Monthly repayment of each customer
3. Top 10 customers by repayment
4. Segment spending analysis
5. Age group spending analysis
6. Most profitable segment
7. Top spending categories
8. Interest applied (2.9%) to due amounts
9. Monthly bank profit

---

## 💰 Profitability Calculation

- **Due Amount = Monthly Spend - Monthly Repayment**
- **Interest = 2.9% on Due Amount**
- **Profit = Repayment + Interest - Spend**

---

## 📌 Tools & Technologies Used

- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **Jupyter Notebook**
- **Data Cleaning & Transformation**
- **Exploratory Data Analysis (EDA)**

---

## 📂 Folder Structure

```bash
📦credit-card-analysis/
 ┣ 📊 data/Credit-Banking_Project - 1
 ┣ 📄 credit_card_analysis.ipynb
 ┗ 📄 README.md

