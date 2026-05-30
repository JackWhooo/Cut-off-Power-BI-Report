<h1 align="center">
  <b>Analytics Dashboard for Accounts Payable </b>
</h1>

<div align="center">
  <a href="#"><img src="https://custom-icon-badges.demolab.com/badge/Power%20BI-F2C811?logo=power-bi&logoColor=fff" alt="Power BI"></a>
  <a href="#"><img src="https://custom-icon-badges.demolab.com/badge/DAX-0078D4?logo=microsoft&logoColor=fff" alt="DAX"></a>
  <a href="#"><img src="https://img.shields.io/badge/Power%20Query-5E9624?logo=microsoftexcel&logoColor=fff" alt="Power Query"></a>
  <a href="#"><img src="https://img.shields.io/badge/Data%20Modelling-00599C?logo=microsoftsqlserver&logoColor=fff" alt="Data Modelling"></a>
</div>

## 📌 Executive Summary
Finance and external audit procedures are traditionally manual and spreadsheet-heavy workflows. I engineered this Power BI project to bridge **External Audit Methodology** with **Finance Transformation**. 

This interactive analytics solution transforms static Accounts Payable (AP) procedures into a dynamic, parameter-driven workflow—automating cut-off testing, anomaly detection, and aging analysis. It demonstrates how scalable data modelling can reduce manual hours, improve transparency, and adapt instantly to different materiality thresholds.

---

## 📌 Technical Architecture & Skills Demonstrated

* **Power BI & Data Storytelling:** Designed an intuitive UI with interactive drill-throughs, dynamic slicers, and conditional formatting to instantly surface high-risk transactions.
* **DAX (Data Analysis Expressions):** Engineered complex, dynamic measures enabling users to manipulate materiality thresholds and rolling cut-off windows in real-time.
* **Data Modelling (Star Schema):** Built a robust, performance-optimised relational model connecting Fact tables (Transactions, AP Listing) with Dimension tables (Vendors, Dates).
* **Power Query:** Automated the ETL (Extract, Transform, Load) pipeline to clean and standardise raw financial datasets.



## Key Features
- Dynamic cut-off window
- Adjustable materiality thresholds
- Drill-through transaction review
- AP aging analytics
- Interactive visualisations

## Dashboard Preview

![Dashboard](screenshots/executive_summary.png)


## Business Problem

External audit procedures are often highly manual and spreadsheet-driven. 
I built this Power BI project to transform traditional audit procedures into interactive analytics workflows.

This dashboard transforms these procedures into an interactive analytics solution that allows users to:
- dynamically adjust cut-off periods,
- change materiality thresholds,
- investigate transactions,
- and drill into invoice-level details.
By including the interactive elements, I have made it flexible to be catered to each specific client with different materiality levels.

## Data Model

The dashboard integrates:
- AP listing
- Transaction listing
- Date dimension table

Relationships were established using:
- Invoice IDs
- Vendor dimensions
- Date dimensions

![Data Model](docs/data_model.png)


## Dashboard Features

| Feature                | Business Purpose                  |
| ---------------------- | --------------------------------- |
| Dynamic Cut-Off Window | Analyse transactions around YE    |
| Threshold Parameter    | Simulate audit materiality        |
| Aging Dashboard        | Identify overdue liabilities      |
| Drill-Through          | Investigate invoice-level details |
| Debit Balance Review   | Detect unusual AP balances        |

## End-to-end Use Case
1. Dynamic Cut-Off Testing

Interactive Features:
- Cut-off days selector
- Threshold slicer

Users can:
- Adjust cut-off window (X days before/after year-end) and select the desired threshold,
- Analyse transaction volumes around YE,
- Identify high-value transactions above threshold (highlighted automatically) near YE.
- Analyse transaction trend
- Analyse transaction amounts by vendor via the scatter chart
- Drill-through to Transaction Details directly

[sreenshot]

2. Accounts Payable Aging Analysis

The dashboard includes:
- aging bucket analysis,
- vendor-level aging review,
- overdue invoice tracking.

Users are able to drill-through to all the accounts payable to any supplier and to the summary of all the invoices in a certain age bucket.

[sreenshot]


## Skills Developed

Through this project I developed:
- Power BI dashboard development
- DAX measures and calculated columns
- Dynamic parameter-driven analysis
- Audit analytics design
- Data modelling and relationships
- Drill-through reporting
- Business-focused data storytelling

## Why This Project Matters

This project demonstrates how data analytics tools can modernise traditional audit procedures by improving:
- efficiency,
- transparency,
- scalability,
- and risk identification.

The project reflects the growing importance of analytics and automation within finance and audit functions.



1. Project Overview
2. Business Problem
3. Dashboard Features
4. Data Model
5. Files Included
6. Prerequisite Knowledge



## Files Included
| File                                         | Description              |
| -------------------------------------------- | ------------------------ |
| `Audit Analytics Solution for AP Review.pbit`  | Power BI dashboard       |
| `Modified_ dummy_AP_Listing_v2.csv`            | Accounts Payable dataset |
| `Modified_ dummy_Transaction_Listing_v2.csv`   | Transaction dataset      |
| `README.md`                                  | Project documentation    |


P.S.
Example data presented in the project is fictional for illustration

# 6. Prerequisite Knowledge

Power BI
- Interactive dashboards
- Drill-down & drill-through
- Dynamic slicers
- Conditional formatting
- KPI cards
- DAX
- Measures
- Calculated columns
- Dynamic filtering
- Visualisation

Data Modelling
- Star schema
- Relationship modelling
- Date table creation

Finance Knowledge
- Cut-off testing
- Aging analysis
- AP review procedures
- Working capital analysis



