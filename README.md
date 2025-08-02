# 🏦 Bank Loan Analysis Dashboard | Power BI & SQL Project

This repository contains a **Data Analyst Portfolio Project** focused on analyzing a bank’s loan data using **MS SQL Server** and **Power BI**. The project includes data extraction, transformation, analysis, and interactive visualization dashboards that help stakeholders make data-driven decisions about loan issuance, repayment, and borrower behavior.

---

## 📂 Project Structure

- 📊 `Bank Loan Report.pbix`: Power BI report file containing all dashboards.

---

## 💡 Objective

The goal of this project is to explore, analyze, and visualize loan application data to generate insights about:

- Total loan applications and their monthly trends
- Disbursed (funded) loan amounts
- Amounts received (repayments)
- Loan performance (good vs. bad loans)
- Borrower profile analysis (region, purpose, employment length, etc.)

---

## 🧠 Problem Statements & Dashboards

### 📌 Dashboard 1: Summary View

A high-level KPI dashboard including:

- **Total Loan Applications** (with MTD & MoM tracking)
- **Total Funded Amount** (MTD & MoM)
- **Total Amount Received** (MTD & MoM)
- **Average Interest Rate** (MTD & MoM)
- **Average Debt-to-Income Ratio (DTI)** (MTD & MoM)

#### Good vs. Bad Loan KPIs:

- Good Loan % | Applications | Funded Amount | Received Amount
- Bad Loan % | Applications | Funded Amount | Received Amount

#### Loan Status Grid View:

Categorized metrics for better decision-making:
- Loan Status-wise: Applications, Funded Amount, Amount Received, MTD values, Avg. Interest Rate, Avg. DTI

---

### 📌 Dashboard 2: Overview View

A comprehensive visual breakdown using:

- 📈 **Monthly Trends (Line Chart)**: Detect seasonality in lending.
- 🗺️ **Regional Analysis (Filled Map)**: State-wise loan distribution.
- 🍩 **Loan Term (Donut Chart)**: Distribution of loans by duration.
- 📊 **Employment Length (Bar Chart)**: Employment vs loan metrics.
- 📊 **Loan Purpose (Bar Chart)**: Purpose-wise loan analysis.
- 🌳 **Home Ownership (Tree Map)**: Effect of home ownership.

All charts include metrics like:
- Total Loan Applications
- Total Funded Amount
- Total Amount Received

---

### 📌 Dashboard 3: Details View

A "single-window" dashboard offering a **comprehensive table view** of all key loan data, borrower profiles, and loan performance indicators for deeper exploration.

---

## 🛠️ Tools & Technologies

| Tool               | Purpose                         |
|--------------------|----------------------------------|
| **MS SQL Server 19.0**       | Data cleaning, querying, modeling |
| **SQL Server Management Studio (SSMS)** | Writing queries, managing DB |
| **Power BI (June 2023)**     | Visualizations and dashboards |
| **Excel 2021**               | Basic data review and support |

---

## 🧰 Key SQL Concepts Used

- Database & table creation
- Aggregations: `COUNT()`, `SUM()`, `AVG()`, `DISTINCT`
- Date functions: `DATENAME()`, `DATEPART()`, `MONTH()`, `DAY()`, `HOUR()`, `QUARTER()`
- CTEs & Window Functions (`PARTITION BY`)
- Data formatting using `CAST()` and `DECIMAL()`
- `GROUP BY`, `ORDER BY`, `LIMIT`

---

## 📈 Power BI Concepts Applied

- SQL Server Connection
- Power Query transformations
- DAX functions: `CALCULATE`, `SUMX`, `FILTER`
- KPIs & Time Intelligence (MTD, MoM)
- Visuals: Card, Line, Bar, Donut, Tree Map, Maps
- Drill-through & Navigation setup
- Interactive Dashboards with slicers

---

## 📚 Learning Outcomes

✔️ Real-world data analysis using SQL and Power BI  
✔️ Hands-on KPI creation and trend analysis  
✔️ Multi-level dashboards for executives and analysts  
✔️ End-to-end pipeline: Raw data → SQL → Power BI → Insightful visuals

---
