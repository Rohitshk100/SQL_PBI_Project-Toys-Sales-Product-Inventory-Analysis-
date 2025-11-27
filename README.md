# SQL_PBI_Project-Toys-Sales-Product-Inventory-Analysis-
This project provides a complete end-to-end data analysis covering Sales Trends, Store Performance, Product Insights, and Inventory Health using SQL and Power BI.

The objective is to understand how different stores, locations, and product categories performed across 2022–2023, and how inventory levels relate to sales behaviour.

# Dataset Description
All datasets are provided in csv format:

sales.csv - Transaction-wise sales with date, store, product, quantity, and revenue

store.csv -	Store master data including store name, city, and location area

product.csv -	Product master data with product category and attributes

inventory.csv -	Inventory levels by store and product

#  Tools & Technologies Used
1. SQL Server

Used for:
Data cleaning & preparation
Joining sales, store, product, and inventory tables
Finding trends, rankings, and relationships
Performing aggregations across years and months

2. Power BI

Used for:
Building interactive dashboards
Time-series analysis
Store performance comparison
Product demand insights
Inventory health visualization

3. Excel

Used for:
Initial data format
Basic checks before loading to SQL/Power BI

# Project Architecture / Workflow
Excel Files  →  SQL Server (Data Cleaning + Analysis)  →  Power BI Dashboard


Load datasets from Excel to SQL Server
Perform data cleansing (date formatting, NULL handling, datatype corrections)
Execute SQL queries for trend, ranking, and relationship analysis
Load cleaned SQL views/tables into Power BI
Build an interactive dashboard covering all KPIs
Publish dashboard with drill-down & filters

📈 Power BI Dashboard Includes

✔ Monthly Sales Trend (2022–2023)

✔ Top/Bottom 5 Stores

✔ Category Demand Analysis

✔ Store Location Impact

✔ Product–Store Sales Heatmap

✔ Inventory Health Metrics
## SQL commands have been added in the file "SQL Commands"

# 🚀 Conclusion

This project provides a comprehensive analytical framework to understand:

Year-over-year sales behaviour

Store performance variations

Product demand across categories and regions

Inventory efficiency

It brings together SQL-based analytical rigor and Power BI storytelling to deliver actionable business insights.

