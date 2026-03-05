# Customer-churn-intelligence-data-analytics

## Project Overview
This project focuses on analyzing bank customer churn using Microsoft Power BI. The goal is to identify patterns that lead to customer attrition and provide insights that can help improve customer retention strategies.

The dashboard provides an interactive view of customer demographics, financial information, and engagement levels to help uncover key drivers of churn.

---

## Objectives
- Analyze customer churn patterns
- Identify factors influencing customer attrition
- Provide data-driven insights for improving customer retention
- Build an interactive dashboard using Power BI

---

## Tools and Technologies
- Microsoft Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Microsoft Excel

---

## Dataset Information
The dataset contains information about **10,000 bank customers**, including demographic details, financial data, and customer engagement indicators.

### Dataset Features
- CreditScore – Customer credit score
- Geography – Customer location
- Gender – Customer gender
- Age – Customer age
- Tenure – Years with the bank
- Balance – Account balance
- NumberOfProducts – Number of bank products owned
- HasCreditCard – Indicates if the customer owns a credit card
- ActiveMember – Indicates if the customer is an active member
- EstimatedSalary – Estimated annual salary
- Churned – Indicates whether the customer left the bank

---

## Data Preparation
Before building the dashboard, the dataset was cleaned and transformed using Power Query:

- Removed unnecessary identification columns
- Renamed columns for better clarity
- Converted binary values into readable categories
- Created an **AgeGroup** column for better segmentation
- Structured the dataset for visualization

---

## Key Performance Indicators (KPIs)
The dashboard includes the following KPIs:

- Total Customers
- Churned Customers
- Customer Churn Rate
- Average Customer Balance

---

## Dashboard Visualizations
The Power BI dashboard includes the following analyses:

- Total Customers
- Churned Customers
- Churn Rate
- Average Balance
- Churn by Geography
- Churned by Gender
- Count by AgeGroup
- Churn by Number of Products
- Customer Activity vs Churn
- Balance vs Age 

Interactive filters/slicers allow users to explore churn patterns by geography, gender, product usage, and customer activity.

---

## Key Insights
- Customers in certain regions show higher churn rates.
- Customers with only one product are more likely to churn.
- Inactive members are significantly more likely to leave the bank.
- Older customer segments show higher churn behavior.

---

## How to Use
1. Clone or download this repository
2. Open the `.pbix` file using Microsoft Power BI Desktop
3. Explore the dashboard and interact with the filters
