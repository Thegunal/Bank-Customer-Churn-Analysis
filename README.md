# Bank Customer Churn Analysis

## Project Overview

Customer churn is a major challenge for banks because losing existing customers is often more expensive than acquiring new ones. This project analyzes customer churn patterns in a European bank using Python, SQL, and Power BI to identify high-risk customer segments and provide actionable business recommendations.

The project follows an end-to-end analytics workflow, including data cleaning, exploratory analysis, business intelligence reporting, and customer risk profiling.

---

## Problem Statement

A European bank is experiencing significant customer churn. The objective of this project is to:

* Identify the factors contributing to customer churn.
* Discover high-risk customer segments.
* Analyze customer behavior across demographics and products.
* Build an interactive dashboard for business stakeholders.
* Provide recommendations to improve customer retention.

---

## Project Workflow

### 1. Data Cleaning (Python & Pandas)

The raw dataset was cleaned and transformed using Python and Pandas.

Tasks performed:

* Handled missing values
* Removed duplicates
* Standardized column formats
* Created derived fields for analysis
* Prepared the dataset for SQL and Power BI

### 2. Business Analysis (SQL)

SQL was used to perform exploratory and business-focused analysis, including:

* Overall churn analysis
* Churn by geography
* Churn by age group
* Churn by product ownership
* Churn by activity status
* Churn by complaints
* Customer segmentation analysis

### 3. Dashboard Development (Power BI)

An interactive dashboard was created to visualize customer churn trends and support decision-making.

### 4. Customer Risk Profiling

A dedicated risk profiling view was built to identify customer segments with the highest likelihood of churn.

---

## Tools & Technologies

| Tool     | Purpose                                 |
| -------- | --------------------------------------- |
| Python   | Data Cleaning                           |
| Pandas   | Data Transformation                     |
| MySQL    | Business Analysis                       |
| Power BI | Dashboard Development                   |
| GitHub   | Project Documentation & Version Control |

---

## Dashboard Features

* Interactive Dashboard Navigation
* Customer Risk Profile View
* Churn KPI Monitoring
* Geography-Based Churn Analysis
* Age Group Churn Analysis
* Product Ownership Analysis
* Complaint Churn Monitoring
* Gender-Based Filtering
* Interactive Visualizations

---

## Key Performance Indicators (KPIs)

### Overall Churn Rate

Measures the percentage of customers who left the bank.

### Churned Customers

Total number of customers who exited the bank.

### Complaint Churn Rate

Measures churn among customers who raised complaints.

### Average Lost Balance

Average customer balance lost due to churn.

---

## Key Business Insights

### Geography Analysis

Germany shows the highest customer churn rate among all regions.

### Age Analysis

Customers aged 51 and above exhibit significantly higher churn behavior compared to younger age groups.

### Product Analysis

Customers with fewer banking products are more likely to leave the bank.

### Complaint Analysis

Customers who submit complaints demonstrate extremely high churn rates, indicating dissatisfaction as a major churn driver.

### Activity Status

Inactive customers are considerably more likely to churn than active customers.

---

## Business Recommendations

### Improve Customer Retention Programs

Focus retention campaigns on high-risk customer segments.

### Strengthen Complaint Resolution

Implement faster complaint handling and customer support improvements.

### Increase Product Adoption

Encourage customers to use multiple banking products through targeted offers and cross-selling.

### Re-engage Inactive Customers

Launch personalized campaigns for inactive customers to improve engagement.

### Focus on High-Risk Demographics

Develop targeted retention strategies for older customers and high-risk regions.

---

## Dashboard Preview

### Main Dashboard

![Dashboard](Screenshots/dashboard.png)

### Customer Risk Profile

![Customer Risk Profile](Screenshots/customer_risk_profile.png)

---

## Project Structure

```text
Bank-Customer-Churn-Analysis/
│
├── Data_Cleaning/
│   └── data_cleaning.ipynb
│
├── SQL_Analysis/
│   └── business_analysis.sql
│
├── PowerBI/
│   └── Bank_Customer_Churn.pbix
│
├── Dataset/
│   └── bank_churn_clean.csv
│
├── Screenshots/
│   ├── dashboard.png
│   └── customer_risk_profile.png
│
└── README.md
```

---

## Conclusion

This project demonstrates a complete data analytics workflow from data cleaning and SQL analysis to dashboard development and business recommendations. The insights generated can help banks better understand customer behavior, reduce churn, and improve customer retention strategies.
