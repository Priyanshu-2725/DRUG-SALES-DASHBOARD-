# 💊 Drug Sales Sales Dashboard | Power BI Analytics Project

> An interactive Power BI dashboard built to analyze pharmaceutical sales performance through customer demographics, product analytics, geographic insights, and time-series trends. This project demonstrates data modeling, Power Query transformations, DAX calculations, and business intelligence visualization.

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=flat-square)
![Power Query](https://img.shields.io/badge/Power_Query-217346?style=flat-square)
![Status](https://img.shields.io/badge/Status-Completed-00B894?style=flat-square)

---

# 📊 Dashboard Preview

> **Dashboard screenshots will be added soon.**

<!-- Replace after uploading -->
<!-- ![Dashboard](images/dashboard.png) -->

---

# 📋 Table of Contents

- Project Overview
- Business Problem
- Dataset
- Data Modeling
- Dashboard Features
- Tech Stack
- Dashboard Pages
- KPIs
- Business Insights
- Project Workflow
- Repository Structure
- Installation
- Skills Demonstrated
- Learning Outcomes
- Author

---

# 🎯 Project Overview

This project presents a complete Business Intelligence solution for analyzing pharmaceutical sales data using Power BI.

The dashboard combines sales transactions, customer demographics, and product information into an interactive reporting solution that enables users to monitor revenue, profitability, customer behavior, and sales trends across multiple dimensions.

The project demonstrates an end-to-end Power BI workflow including:

- Data Cleaning
- Data Transformation
- Data Modeling
- DAX Calculations
- Dashboard Development
- Business Insight Generation

---

# 🔴 Business Problem

Organizations often struggle to analyze large volumes of sales data spread across multiple datasets.

This dashboard answers important business questions such as:

- Which drugs generate the highest revenue?
- Which products are most profitable?
- Which countries contribute the highest sales?
- Which customer demographics purchase the most?
- How do sales change over months and years?
- Which buyer types generate maximum revenue?

---

# 📂 Dataset

The dashboard is built using three interconnected datasets.

### Customers

Contains demographic information:

- Customer ID
- Age
- Gender
- Country

---

### Drugs

Contains product details:

- Drug ID
- Drug Name
- Unit Price
- Cost
- Disease Treated

---

### Sales

Contains transactional information:

- Sale ID
- Customer ID
- Drug ID
- Units Sold
- Sale Date
- Buyer Type

---

# ⭐ Data Model

The dashboard follows a **Star Schema**.

```
Customers
      |
      |
Sales Fact Table
      |
      |
Drugs
```

This model improves query performance and simplifies DAX calculations.

---

# 🛠 Tech Stack

- Power BI Desktop
- Power Query
- DAX
- Microsoft Excel
- SQL

---

# 📈 Dashboard Features

## Executive Dashboard

Includes KPIs such as:

- Total Revenue
- Total Cost
- Net Profit
- Profit Margin
- Units Sold
- Average Order Value

---

## Product Analysis

- Top Selling Drugs
- Bottom Performing Drugs
- Revenue by Drug
- Profit by Drug
- Units Sold by Product

---

## Customer Analytics

- Revenue by Gender
- Revenue by Age Group
- Revenue by Buyer Type
- Customer Distribution
- Customer Segmentation

---

## Geographic Analysis

- Revenue by Country
- Country-wise Profit
- Regional Performance
- Market Comparison

---

## Time Series Analysis

- Monthly Sales Trend
- Quarterly Revenue
- Yearly Revenue
- Weekly Sales
- Daily Sales Trend

---

# 📊 Dashboard Pages

## Page 1 — Sales Overview

Displays:

- KPI Cards
- Revenue Trend
- Top Products
- Profit Analysis
- Sales Summary

---

## Page 2 — Customer Insights

Displays:

- Customer Demographics
- Buyer Type Analysis
- Geographic Distribution
- Country Performance

---

## Page 3 — Sales Trends

Displays:

- Monthly Trends
- Year-over-Year Growth
- Seasonal Analysis
- Weekly Performance

---

# 📌 Key KPIs

- Total Revenue
- Total Cost
- Net Profit
- Profit Margin
- Units Sold
- Average Selling Price
- Average Order Value

---

# 📊 Business Insights

The dashboard helps identify:

- Highest revenue-generating products
- Most profitable customer segments
- Best-performing countries
- Seasonal demand fluctuations
- Sales growth trends
- Customer purchasing behavior

---

# 📈 Recommendations

Based on dashboard insights:

- Increase inventory for top-selling drugs.
- Improve marketing in high-performing regions.
- Focus promotions on profitable customer segments.
- Review low-performing products.
- Optimize inventory using seasonal trends.

---

# 🔄 Project Workflow

```
Raw CSV Files
      ↓
Power Query
      ↓
Data Cleaning
      ↓
Star Schema Modeling
      ↓
DAX Measures
      ↓
Interactive Dashboard
      ↓
Business Insights
```

---

# 📁 Repository Structure

```
DRUG-SALES-DASHBOARD-/

│── Drug Sales Dashboard.pbix
│── Dataset/
│     ├── Customers.csv
│     ├── Drugs.csv
│     ├── Sales.csv
│
│── Images/
│
└── README.md
```

---

# 🚀 Getting Started

## Clone Repository

```bash
git clone https://github.com/Priyanshu-2725/DRUG-SALES-DASHBOARD-.git
```

Open the project folder:

```bash
cd DRUG-SALES-DASHBOARD-
```

Open the `.pbix` file using **Power BI Desktop**.

Refresh the data if required.

---

# 📚 Skills Demonstrated

- Power BI
- Data Visualization
- Data Modeling
- Star Schema
- Power Query
- DAX
- ETL
- Dashboard Design
- Business Intelligence
- Data Analytics

---

# 🎓 Learning Outcomes

Through this project I gained hands-on experience in:

- Designing interactive dashboards
- Building Star Schema models
- Writing DAX measures
- Creating KPIs
- Power Query transformations
- Business storytelling with data
- Interactive reporting

---

# 📄 License

This project is shared for educational and portfolio purposes.

---

# 👨‍💻 Author

## Priyanshu Sharma

**GitHub**

https://github.com/Priyanshu-2725

**Project Repository**

https://github.com/Priyanshu-2725/DRUG-SALES-DASHBOARD-

---

# ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

Suggestions and feedback are always welcome!

---

Turning Data into Business Decisions with Power BI 💊📊