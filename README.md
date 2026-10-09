# 📉 Telecom Customer Churn Analysis

## 📌 Project Overview

This project focuses on Exploratory Data Analysis (EDA) and diagnostic analysis of telecom customer churn using Python. The goal is to understand why customers leave the service, identify high-risk customer segments, analyze revenue loss, and develop data-driven strategies to improve customer retention.

The project explores customer demographics, contract types, offers, internet services, payment methods, tenure, billing patterns, and churn behavior.

## 🎯 Business Objectives

- Understand the overall customer churn problem.
- Identify the key factors influencing customer cancellations.
- Analyze churn across contracts, offers, payment methods, and services.
- Investigate customer tenure and billing patterns.
- Quantify revenue associated with churned customers.
- Identify high-risk customers for proactive retention campaigns.
- Recommend actionable strategies to improve customer loyalty.

## 🛠️ Tools & Technologies

- **Python** – Data analysis and manipulation.
- **Pandas** – Data cleaning, transformation, and aggregation.
- **NumPy** – Numerical operations and feature engineering.
- **Matplotlib** – Data visualization.
- **Seaborn** – Statistical visualization.
- **SciPy** – Statistical testing.
- **Jupyter Notebook / Google Colab** – Interactive analysis environment.

## 📂 Dataset Overview

The dataset contains customer information related to telecom services, account details, billing, customer status, and churn reasons.

Key attributes explored include:

- Customer demographics: Age, Gender, Married, Dependents.
- Account information: Tenure, Contract, Offers, Referrals.
- Services: Internet Type, Online Security, Tech Support, Streaming Services.
- Billing and payments: Monthly Charge, Total Charges, Total Revenue, Payment Method.
- Churn information: Customer Status, Churn Category, Churn Reason.


## 💡 Key Business Insights

- **Revenue Impact:** Approximately $3.68 million in revenue was associated with churned customers, representing about 17% of total revenue in the analysis.
- **Contract Type:** Month-to-month customers showed a high churn rate of approximately 51.69%.
- **Customer Tenure:** Churned customers had an average tenure of around 18 months, compared with more than 41 months for retained customers.
- **Payment Methods:** Bank withdrawal accounted for a large volume of customer losses, while credit card users showed comparatively stronger retention.
- **Monthly Charges:** Customers with higher monthly bills showed higher churn rates than customers with lower bills.
- **Customer Services:** Lack of certain add-on services was associated with higher churn in several customer segments.
- **Geographic Patterns:** San Diego showed a significant retention challenge, while Los Angeles had a high volume of customer cancellations.
- **High-Risk Customers:** Combining short tenure, month-to-month contracts, and the absence of an offer helped identify a customer segment with elevated churn risk.


## 🧠 Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Data cleaning and preprocessing
- Missing-value handling
- Feature engineering
- Pandas and NumPy
- Data visualization with Matplotlib and Seaborn
- Statistical analysis with SciPy
- Churn rate and KPI analysis
- Customer segmentation and risk identification
- Revenue impact analysis
- Business insight generation
- Data-driven recommendations

## 📂 Repository Contents
* `telecom_churn.ipynb`: The primary Jupyter Notebook containing data cleaning, type optimization, and visual diagnostic analysis.
* `telecom_customer_churn.csv`: The raw dataset used for this analysis.

## 🚀 How to Run
1. Clone this repository to your local machine.
2. Ensure you have the required libraries installed (`pip install pandas numpy matplotlib seaborn`).
3. Open `telecom_churn.ipynb` in Jupyter Notebook or Google Colab and run all cells.
