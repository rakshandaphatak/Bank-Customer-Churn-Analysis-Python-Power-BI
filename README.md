# Bank Customer Churn Analysis

# Project description 

This project focuses on analyzing customer churn in a retail bank. Customer churn occurs when clients stop doing business with a bank, which leads to revenue loss and higher acquisition costs. The aim of this project is to identify churn drivers, analyze customer segments, and recommend retention strategies using data analysis and visualization.

# Interactive Dashboard link :

[Click here to View](https://app.powerbi.com/groups/me/reports/52d659b0-9b6e-4cab-bf69-2f5194e292a2/209f44ba25574ca437e6?experience=power-bi)

# Open Notebook in Google Colab :

[Click here to Open](https://colab.research.google.com/github/rakshandaphatak/Bank-Customer-Churn-Analysis-Python-Power-BI/blob/main/Bank_customer_churn_.ipynb#scrollTo=sIBOVftyD8Vf)


# Table Of Contents 

- [Project Description](#2-project-description)  
- [Table of Contents](#3-table-of-contents)  
- [Overview](#4-overview)  
- [Business Problem](#5-business-problem)  
- [Dataset](#6-dataset)  
- [Tools & Technologies](#7-tools--technologies)  
- [Data Cleaning & Preparation](#8-data-cleaning--preparation)  
- [Project Structure](#9-project-structure)  
- [Key Findings](#10-key-findings)  
- [Report Highlights](#11-report-highlights)  
- [How to Use / Run This Project](#12-how-to-use--run-this-project)  
- [Final Recommendations](#13-final-recommendations)  
- [Author & Contact](#14-author--contact)  

# Overview

- Total Customers: 10,000

- Churned Customers: 2,037 (20.37%)

- Active Members: 5,151

- Avg Churned Balance: 91.11K

- The dashboard provides insights into churn across age, gender, geography, balance, tenure, credit card status, and risk groups.

# Business Problem 

- Banks face a major challenge in reducing churn. Losing customers not only lowers profitability but also costs more than retaining existing ones. This project focuses on:

- Understanding churn patterns across demographics, financial behavior, and engagement.

- Building a dashboard for monitoring churn metrics.

- Recommending actionable strategies for retention.

# Dataset

- Size: 10,000 records

- **Key Columns:**

- Customer ID, Age, Gender, Country

- Credit Score, Balance, Tenure, Estimated Salary

- Active Status, Credit Card Ownership

- Churn (Target variable)

# Tools & Technologies

- **Python** :

- Pandas (Data Manipulation)

- Matplotlib & Seaborn (EDA & Visualization)

- **Power BI** :

- Data Modeling & Measures

- Interactive Dashboard with filters

- **Excel (initial data exploration)**

# Data Cleaning & Preparation 

- **Created new segments:**

- Age Group

- Balance Group

- Credit Score Group

- Converted data types and standardized formats.

- Verified churn rate calculations.

# Analysis Approach

**Python:**

- Cleaned and transformed dataset.

- Performed EDA to calculate churn rates by groups.

- Visualized churn patterns across demographics and financial attributes.

**Power BI:**

- Built an interactive dashboard with KPIs:

- Total Customers, Churned Customers, Churn %

- Avg Churned Balance

- Added filters for Age, Gender, Risk Group, Balance Group.

**Created charts for churn by:**

Tenure

Age Group

Country

Credit Card Ownership

Active Status

Estimated Salary

Credit Score

# Project Structure

Bank-Customer-Churn-Analysis/
│
├── IPYNB File           # IPYNB File 
├── Reports/             # PDF reports  
├── Dashboard/           # Power BI dashboard Screenshot  
├── README.md            # Project documentation  


# Key Findings

- Overall churn rate: **20.37%** (significant impact on profitability).

- Inactive customers churn more **(26.9%)** than active **(14.3%)**.

- **Germany** shows highest churn (32.4%) vs Spain (16.7%) and France (16.2%).

- Age **40–49 group** has the highest churn count (806).

- **High-risk** customers churn rate: 22.68% (vs 7.88% for low risk).

- **No credit card** customers churn nearly 50%.

- **High balance customers** churn more (25.2%) than low balance (14.2%).

- **Credit score** does not strongly predict loyalty (all ~20%).

# Report Highlights

**Customer Overview** – Total customers, churned customers, churn %

**Churn by Demographics** – Age group, gender, and geography trends

**Churn by Customer Engagement** – Active vs inactive customers

**Churn by Financial Attributes** – Balance group, credit score, and estimated salary

**Churn by Services** – Credit card ownership and tenure analysis

**Risk Segmentation** – High-risk vs low-risk churn comparison

**Key Drivers of Churn** – Identification of top contributing factors

**Recommendations** – Actionable strategies to reduce churn

# How to run this project 

- Clone the repository or download the folder.

- Open the **Power BI file (.pbix)** to explore the dashboard.

- Refer to the **PDF reports** for summary insights.

- Open the **Power BI secreenshot**.

- Open the **IPYNB File** to explore python codes and outputs.

# Final Recommendations

- Engage **inactive customers** with personalized campaigns.

- Investigate churn causes in **Germany** (fees, competition, service issues).

- Offer reward-based or low-fee **credit cards** to reduce churn among cardless users.

- Strengthen relationships with **high-risk and high-value customers** (dedicated managers, financial advice).

- Develop tailored financial products for the **40–49 age group**.

- Monitor customer satisfaction using surveys and feedback loops.

# Author & Contact 

👩‍💻 Author: Rita Nayak

📧 Email: [rakshanda5193@gmail.com]

🔗 LinkedIn: [https://www.linkedin.com/in/rakshanda-phatak/]
