# Telecom-Customer-Churn-Analysis

## 📌 Project Overview

This project analyzes customer churn in a telecom company using customer demographic, service, contract, and billing data.

The goal is to identify the main factors associated with customer churn and generate useful business insights for customer retention.

## 📊 Dataset

- **Customers:** 7,043
- **Columns:** 21
- **Target:** Churn
- **Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn

### Main Features
- Customer demographics
- Tenure
- Internet and telecom services
- Contract type
- Payment method
- Monthly and total charges
- Churn status

## 🧹 Data Cleaning

- Checked dataset structure using `head()` and `info()`
- Converted `TotalCharges` to numeric
- Replaced blank `TotalCharges` values with 0
- Checked for missing values
- Checked duplicate customer IDs
- Converted `SeniorCitizen` values from 0/1 to No/Yes

## 📈 Analysis Performed

The project analyzes churn based on:

- Gender
- Senior Citizen status
- Customer tenure
- Contract type
- Internet service
- Additional services
- Payment method

## 🔍 Key Findings

- Overall customer churn is **26.54%**.
- Month-to-month customers have the highest churn rate at about **42%**.
- One-year and two-year contract customers have churn rates of about **11%** and **3%**.
- Electronic check users have the highest churn rate at about **45%**.
- Customers with less than one year of tenure have about **50%** churn.
- Fiber Optic customers show about **30%** churn.
- Senior citizens show about **41%** churn.

## 💡 Business Recommendations

- Encourage customers to choose long-term contracts.
- Improve engagement during the first year.
- Investigate reasons for high electronic-check churn.
- Develop targeted retention programs for senior customers.
- Investigate service quality and customer satisfaction among Fiber Optic users.

## 🛠️ Technologies

```text
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
