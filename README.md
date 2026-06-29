# 🛡️ Insurance Performance Analytics Dashboard | Power BI

## 📌 Overview

The **Insurance Performance Analytics Dashboard** is an end-to-end Business Intelligence project developed using **Microsoft Power BI** to analyze insurance policy data and generate meaningful business insights.

The dashboard is built on a **fictional insurance dataset** and demonstrates how Power BI can be used to monitor premium collections, maturity values, investment returns, policy performance, and sales analytics through interactive visualizations.

This project focuses on transforming raw insurance data into an executive-level dashboard that enables quick decision-making through dynamic KPIs, slicers, drill-down analysis, and interactive charts.

---

## 🎯 Project Objectives

The primary objectives of this project are to:

* Analyze insurance premium collections and maturity values.
* Track policy performance across different policy types and protection plans.
* Evaluate investment returns using Annualized ROI and CAGR.
* Monitor premium payment trends and profitability.
* Compare sales performance across agents and geographical locations.
* Build a clean, interactive dashboard suitable for executive reporting.

---

## 📊 Dashboard Features

### Executive KPI Cards

The dashboard provides high-level business metrics including:

* Total Number of Policies
* Total Premium Amount
* Total Annual Premium
* Total Premium Paid
* Total Premium Payable
* Total Underwriting Expense

---

### Interactive Filters

Users can dynamically filter the dashboard using:

* Policy Type
* Policy Name
* Sales Agent
* Year
* State
* Occupation
* Visual Parameter
* Payment Bucket
* Policy Tenure

---

### Interactive Visualizations

The dashboard includes:

* KPI Cards
* Pie Charts
* Donut Charts
* Treemaps
* Clustered Bar Charts
* Combo Charts
* Line Charts
* Matrix Reports
* Dynamic Visual Parameter Switching

---

## 📈 Business KPIs

The dashboard calculates and visualizes several important insurance business metrics, including:

* Total Premium Amount
* Total Annual Premium
* Total Premium Paid
* Total Premium Payable
* Maturity Amount
* Profit / Gain
* Annualized ROI (%)
* CAGR (%)
* Underwriting Expense
* Sum Assured
* Premium Payment Duration

---

## 📌 Business Insights Generated

The dashboard enables users to answer questions such as:

* Which policy plans generate the highest premium?
* Which policy types contribute the most revenue?
* Which sales agents generate the maximum premium?
* Which states have the highest insurance business?
* Which occupations purchase the highest-value policies?
* How does Annualized ROI change over time?
* Which policies are maturing in the next 5, 10, 15, and 20 years?
* How much premium has been collected versus how much remains payable?

---

## 🧮 DAX Measures Used

Some of the key DAX calculations implemented include:

* Total Premium Amount
* Total Annual Premium
* Total Premium Paid
* Total Premium Payable
* Maturity Amount
* Profit / Gain
* Annualized ROI (%)
* CAGR (%)
* Maturity Buckets
* Dynamic KPI Measures
* Visual Parameter Measures

---

## 📂 Data Model

The project follows a relational data model consisting of a central fact table connected with multiple dimension tables.

### Fact Table

* FCT Insurance Policy Table

### Dimension Tables

* Customer Details
* Insurance Agents
* Policy Protection Plan
* Policy Type
* Regional Manager
* Zonal Manager

---

## 📈 Dashboard Pages

### 1. Executive Summary

Provides a high-level overview of:

* Total Policies
* Premium Collection
* Premium Payable
* Underwriting Expenses
* Premium Distribution
* Sales Performance
* Geographic Analysis

---

### 2. Investment & Maturity Analysis

Focuses on:

* Premium vs Maturity Amount
* Annualized ROI
* CAGR
* Sum Assured
* Future Maturity Analysis
* Policy Tenure Analysis

---

### 3. Premium Analysis

Includes:

* Premium Paid vs Premium Payable
* Sales Agent Performance
* Regional Performance
* Zonal Performance
* Payment Bucket Analysis
* Year-wise Premium Trends

---

## 🛠 Technologies Used

* Microsoft Power BI
* Power Query
* DAX (Data Analysis Expressions)
* Data Modeling
* Business Intelligence
* Data Visualization

---

## 🎨 Dashboard Design Highlights

The dashboard follows modern BI design principles including:

* Executive-style KPI cards
* Professional color palette
* Interactive slicers
* Consistent typography
* Responsive layout
* Cross-filtering
* Drill-down analysis
* Dynamic visual switching

---

## 📁 Repository Structure

```
Insurance-Performance-Dashboard/

│── Dashboard.pbix
│── Dataset/
│     ├── Insurance_Data.xlsx
│
│── Images/
│     ├── Dashboard Overview.png
│     ├── Premium Analysis.png
│     ├── Investment Analysis.png
│
│── README.md
```

---

## 🚀 Key Skills Demonstrated

* Business Intelligence
* Dashboard Design
* Data Modeling
* DAX
* Power Query
* Data Visualization
* KPI Development
* Executive Reporting
* Interactive Analytics
* Insurance Domain Analytics

---

## 📸 Dashboard Preview

> Add screenshots of the dashboard here.

Example:

```
Images/
    Dashboard Overview.png
```

```markdown
![Dashboard](Images/Dashboard%20Overview.png)
```

---

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

* Building interactive Power BI dashboards
* Writing business-focused DAX calculations
* Designing executive-level reports
* Creating dynamic visualizations
* Developing insurance-related business KPIs
* Applying professional dashboard design principles

---

## 🔮 Future Improvements

Potential enhancements include:

* Real-time data integration using SQL Server or Azure
* Predictive premium forecasting
* Customer segmentation using Machine Learning
* Claim analytics dashboard
* Policy lapse prediction
* Power BI Service deployment with Row-Level Security (RLS)

---

## 👨‍💻 Author

**Shivansh Tomar**

If you found this project useful or have any suggestions, feel free to connect or raise an issue in this repository.
