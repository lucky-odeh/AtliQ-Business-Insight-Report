# AtliQ Business Insight Report
---
## Project Overview
AtliQ hardware is a rapidly growing company in recent years, and they have
decided to implement data analytics into their business process for the first time to enable them track trends, stay competitive and to make data driven decision.
## Objectives
The goal of this project is to create an interactive dashboard for various business stakeholders that displays revenue figures and performance of the company across different markets, industry, products and customers. 
## Key Qestions
1. Who are the company's top customers in terms of revenue generated?
2. What are the top performing products and least performing products in terms of revenue?
3. What has been the trend of the market share of the company over the years?
4. Which market is the company performing the most?
5. What is the demand forecast of the company in terms of forecast accuracy?
## Data Collection
The dataset used for this analysis contains over a million records with attributes such as "dim_customers", "dim_products", "dim_market", "facts_sales", "facts_forecast_sales" amongst others. These dataset was domiciled in MySQL database, and Power BI was connected to the database to extract the data, and then transformed and loaded in power query.
### Tools used:
- MySQL database: Data storage and validation
- Power BI: Extract, Transform, Load and performing exploratory analysis
## Data Cleaning & Preparation in Power Query
### Steps taken:
1. **Duplicate Removal:** some of the data contained duplicates which were eliminated
2. **Replacing value:** replaced some data fields due to spelling mistakes to ensure data integrity
3. **Change Data type:** applied the right data types for each of the columns in the table
4. **Join Operations:** applied the "merge query" function in power query to join multiple tables based on columns relationship
5. **Custom table:** created a date dimension table using M-language
### Outcome:
Cleaned and structured data, ready for analysis and visualization

## Data Modeling
Established relationship betweeb key tables: dimension tables and the facts tables as seen below




