# Global Electronics Retail Power BI Dashboard

## Project Overview

This project presents an end-to-end Business Intelligence solution developed in **Power BI** using the **Global Electronics Retail Dataset** from Maven Analytics.

The objective was to transform raw transactional data into interactive dashboards that provide business leaders with actionable insights into sales performance, profitability, product performance and customer behaviour across multiple countries.

---

## Business Problem

Business leaders require a centralised reporting solution to monitor organisational performance and support data-driven decision making.

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
- Built a Star Schema data model
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

![Data Model](Data%20Model.png)

---

## Power Query

Power Query was used to clean, transform and prepare the data before loading into the model.

![Power Query](Power%20Query.png)

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

![Executive Dashboard](Executive%20Business%20Performance.png)

---

## 2️. Sales & Product Performance Dashboard

Analyses product and brand performance through:

- Top Revenue Products
- Top Profit Products
- Revenue vs Profit by Brand
- Category Performance Summary

![Sales Dashboard](Sales%20%26%20Product%20Performance.png)

---

## 3️. Customer & Geographic Insights Dashboard

Explores customer behaviour and geographical performance using:

- Global Revenue Distribution
- Revenue by Geography & Customer Demographics
- Top Revenue Generating Cities
- Revenue vs Customers by Country

![Customer Dashboard](Customer%20%26%20Geographic%20Insights.png)

---

# Key Business Insights

- Computers generated the highest revenue and profit.
- North America contributed the largest share of revenue.
- Physical stores generated the majority of sales.
- Toronto was the highest revenue-generating city.
- Revenue was concentrated across a small number of countries.
- Customer distribution varied significantly by geography.

---

# Tools & Technologies

- Power BI Desktop
- Power Query
- DAX
- Microsoft Excel

---

# Skills Demonstrated

- Business Intelligence
- Dashboard Design
- Data Cleaning
- Data Transformation
- Star Schema Data Modelling
- DAX
- KPI Development
- Data Visualisation
- Data Storytelling
- Executive Reporting

---

# Author

**Aravindh Ravi**

LinkedIn:
https://www.linkedin.com/in/aravindh-ravi-4ar/

GitHub:
https://github.com/Aravindhrav1
