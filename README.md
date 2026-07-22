# Global Electronics Retail Power BI Dashboard

## Project Overview

This project presents an end-to-end Business Intelligence solution developed in **Power BI** using the **Global Electronics Retail Dataset** from Maven Analytics.

The objective was to transform raw transactional data into interactive dashboards that provide business leaders with actionable insights into sales performance, profitability, product performance and customer behaviour across multiple countries.

---

## Business Problem

Business leaders require a centralised reporting solution to monitor performance, identify trends and support data-driven decision-making across products, customers and geographical markets.
This dashboard answers key business questions such as:

- Which products generate the highest revenue and profit?
- Which countries and cities contribute the most revenue?
- How are customers distributed geographically?
- What is the overall business performance?
- Which product categories perform best?

---

## Dataset

**Source:** Maven Analytics – Global Electronics Retail Dataset

The project uses five datasets:

- Sales
- Customers
- Products
- Stores
- Exchange Rates

---

## Data Preparation

The data was transformed using **Power Query**.

Key preparation activities included:

- Removed missing and invalid records
- Standardised date formats
- Corrected data types
- Created Delivery Days
- Cleaned currency fields
- Designed and implemented a Star Schema data model.
- Created a dedicated Date Dimension
- Developed reusable DAX measures

---

## Data Model

A **Star Schema** was implemented to improve report performance and simplify analysis.

Fact Table

- FactSales

Dimension Tables

- DimCustomer
- DimProduct
- DimStore
- DimDate

### Data Model

![Data Model](Images/Data%20Model.png)

---

## Power Query

Power Query was used to clean, transform and prepare the data before loading into the model.

![Power Query](Images/Power%20Query.png)

---

# Dashboard Pages

## 1️. Executive Business Performance Dashboard

Provides an executive overview of:

- Revenue
- Profit
- Profit Margin
- Orders
- Customers
- Average Order Value
- Revenue by Country
- Revenue by Category
- Store Performance

## Dashboard Preview
![Executive Dashboard](Images/Executive%20Business%20Performance%20Dashboard.png)

---

## 2️. Sales & Product Performance Dashboard

Analyses product and brand performance through:

- Top Revenue Products
- Top Profit Products
- Revenue vs Profit by Brand
- Category Performance Summary

## Dashboard Preview
![Sales Dashboard](Images/Sales%20%26%20Product%20Performance.png)

---

## 3️. Customer & Geographic Insights Dashboard

Explores customer behaviour and geographical performance using:

- Global Revenue Distribution
- Revenue by Geography & Customer Demographics
- Top Revenue Generating Cities
- Revenue vs Customers by Country

## Dashboard Preview
![Customer Dashboard](Images/Customer%20%26%20Geographic%20Insights.png)

---

# Key Business Insights

- Computers generated the highest revenue (£19.3M) and profit (£11.3M), making them the best-performing product category.
- North America contributed the majority of total revenue, highlighting its importance as the company's primary market.
- Toronto was the highest revenue-generating city across all locations.
- Physical stores generated a larger share of revenue than online sales.
- Revenue was concentrated across a relatively small number of countries, indicating opportunities for further international growth.

---

## Project Highlights

- End-to-end Business Intelligence solution developed in Power BI
- Star Schema data model for efficient reporting
- Data transformation using Power Query
- Interactive dashboards built with DAX measures and KPIs
- Executive, Sales and Customer analytics dashboards

  ---

# Tools & Technologies

- Power BI Desktop
- Power Query
- DAX
- Microsoft Excel

---

# Skills Demonstrated

### Data Preparation
- Power Query
- Data Cleaning
- Data Transformation

### Data Modelling
- Star Schema
- Relationship Management

### Analysis
- DAX
- KPI Development
- Business Analysis

### Reporting
- Dashboard Design
- Data Visualisation
- Executive Reporting
- Data Storytelling

---

# Future Enhancements

Possible enhancements for future versions include:

- Implement Row-Level Security (RLS)
- Add drill-through pages for detailed analysis
- Support dynamic currency conversion
- Publish to Power BI Service with scheduled refresh
- Connect to live data sources for real-time reporting

---

# Author

**Aravindh Ravi**

LinkedIn:
https://www.linkedin.com/in/aravindh-ravi-4ar/

GitHub:
https://github.com/Aravindhrav1
