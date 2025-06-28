# Data Cleaning & Exploratory Data Analysis (EDA) in Power BI

## Project Overview

This project explores and cleans sales data from the **AdventureWorksDW2022** data warehouse. The goal is to build a clean, analysis-ready data model and uncover key insights into sales trends, product performance, and customer behavior using **Power BI**.

---

## Objectives

- Clean and transform raw fact and dimension tables using Power Query
- Build a star-schema data model with proper relationships
- Create DAX measures for sales KPIs (e.g., Total Revenue, Total Orders, Cumulative Sales)
- Perform exploratory analysis to identify trends in sales, products, and regions

---

## Key Insights

- Top 10 products contributed over 35% of total sales
- North America generated the highest revenue among regions
- Sales showed overall growth from 2010 - 2014
- Returning customers drove more revenue than new customers

---

## Tools & Technologies

- **Power BI Desktop** (data modeling, DAX, visualization)
- **Power Query** (ETL: cleaning and transforming data)
- **DAX** (measures: Total Revenue, Cumulative Sales, Avg Order Value)
- **AdventureWorksDW2022** (SQL Server sample data warehouse)

---

## Data Sources

From the `AdventureWorksDW2022` database:

| Table Name             | Purpose                            |
|------------------------|------------------------------------|
| `FactInternetSales`    | Sales transactions (fact table)    |
| `DimCustomer`          | Customer demographics              |
| `DimProduct`           | Product details                    |
| `DimSalesTerritory`    | Regional sales territories         |
| `DimDate`              | Date hierarchy for time analysis   |

---

## Power BI Report Pages

1. **Overview Dashboard** – Total Sales, Orders, KPIs, trends
2. **Product Performance** – Sales by product and category
3. **Customer & Region Insights** – Revenue by territory, customer type
4. **Sales Trends and Seasonality** – Monthly and cumulative sales analysis
5. **Order Details** – Tabular view of transactions

---

## Files Included

- `Retail_Sales_EDA.pbix` – Full Power BI dashboard file
- `Retail_Sales_EDA.pdf` – Report PDF

---

## Future Improvements

- Incorporate customer lifetime value (CLV) segmentation
- Publish report to Power BI Service for public interactivity

---

## Author

**Vincent Nguyen**  
Aspiring Data Analyst | SQL • Power BI • Data Storytelling 

---

