# SQL Sales & HR Analytics – AdventureWorks (2013)

## 📌 Project Overview

This project analyzes **AdventureWorks 2013 sales and workforce data** using **SQL Server and Power BI** to generate business insights.

The analysis focuses on:

- Revenue performance
- Regional sales distribution
- Product revenue concentration
- Salesperson contribution
- Workforce structure and tenure

The objective is to demonstrate the ability to **extract insights from relational data and communicate findings through dashboards and business analysis**.

---

## 🛠 Tools & Technologies

- **SQL Server (T-SQL)**
- **AdventureWorks Database**
- **Power BI**
- **Data Visualization**
- **Business Intelligence**

---

## 📊 Power BI Dashboard

![Sales Dashboard](dashboard/sales_dashboard_preview.png)

**Dashboard Highlights**

- Monthly revenue trends
- Revenue by sales territory
- Top-performing products
- Salesperson performance comparison
- Interactive territory filtering

---

## 🔑 Key Business Insights

- **Revenue concentration:** Top territories generate a significant share of company revenue.
- **Product dependency:** A small group of products contributes a large portion of total sales.
- **Sales inequality:** Top 3 salespeople generate over **one-third of total revenue**.
- **Seasonality:** Sales peak during **mid-year and early Q4**.
- **Workforce structure:** Over **60% of employees work in production roles**, reflecting an operations-focused organization.

➡️ **Full analysis available here:**  
[View Detailed Insights](insights/insights_summary.md)

---

## 📁 Project Structure

```
SQL-Sales-HR-Analytics
│
├── sql
│   └── adventureworks_sales_hr_analytics.sql
│
├── dashboard
│   ├── dashboard_preview.png
│   └── sales_performance_dashboard_2013.pbix
│
├── insights
│   └── insights_summary.md
│
└── README.md
```

---

## 🧠 Skills Demonstrated

### SQL Techniques

- **JOIN operations** (`LEFT JOIN`) to integrate data across multiple relational tables
- **Aggregate Functions** (`SUM`, `COUNT`) to compute key business metrics such as revenue and employee headcount
- **GROUP BY** to summarize performance by territory, product, salesperson, and department
- **TOP and ORDER BY** to identify best-performing entities (e.g., top products and longest-tenured employees)
- **Window Functions** (`ROW_NUMBER()`, `RANK()`, `OVER(PARTITION BY)`) for ranking customers, months, and departments
- **Window Aggregation** (`SUM() OVER()`) to calculate total revenue and contribution ratios
- **Common Table Expressions (CTEs)** to structure complex analytical queries
- **UNION ALL** to combine results for comparative analysis (e.g., highest vs. lowest revenue months)
- **Date Functions** (`YEAR()`, `MONTH()`, `DATEDIFF()`) for time-based sales and tenure analysis
- **String Functions** (`CONCAT_WS`) to format employee names
- **Data Type Conversion** using `CAST()` for precise numeric calculations
- **Filtering and Conditional Logic** using `WHERE` and `IS NOT NULL`
- **User-Defined Function (UDF)** to calculate employee tenure dynamically

### Analytical Skills

- Revenue concentration analysis by territory
- Product performance evaluation
- Customer contribution identification
- Seasonal revenue trend detection
- Salesperson performance ranking
- Workforce distribution analysis
- Department headcount comparison
- Employee tenure analysis

### Business Intelligence

- Dashboard development using **Power BI**
- KPI design and visualization
- Revenue trend visualization
- Performance comparison across regions and employees
- Data storytelling through interactive dashboards

---

## 📊 Data Source

AdventureWorks2019 Sample Database
A Microsoft sample dataset that simulates a manufacturing and retail business environment.

Key tables used:

Sales:
- Sales.SalesOrderHeader
- Sales.SalesOrderDetail
- Sales.SalesTerritory
- Sales.SalesPerson

Human Resources:
- HumanResources.Employee
- HumanResources.EmployeeDepartmentHistory
- HumanResources.Department