# Project Title: Sales Performance Analysis for a Retail Store

## Table of Contents
[Project Overview](#project-overview)

[Project Objectives](#project-objectives)

[Data Source](#data-source)

[Tool Used](#tool-used)

[Data Analysis Process](#data-analysis-process)


### Project Overview
---
This project aims to provide a comprehensive analysis of sales data for a retail store, identifying key insights to improve business strategies and drive sales growth. Through this analysis, we explore product performance, regional sales distribution, and monthly sales trends to uncover factors contributing to revenue and customer demand patterns using SQL.

### Project Objectives
---
The objective is to;

- retrieve the total sales for each product category.
- find the number of sales transactions in each region.
- find the highest-selling product by total sales value.
- calculate total revenue per product.
- calculate monthly sales totals for the current year.
- find the top 5 customers by total purchase amount.
- calculate the percentage of total sales contributed by each region.
- identify products with no sales in the last quarter.

### Data Source
---
The dataset used for this analysis was provided by the course facilitator as part of the capstone project for data analysis training.

### Tool Used
---
- SQL [Structured Query Language]
  1. For Data import 
  2. For Cleaning
  3. For Analysis

  ###  Data Analysis Process
---

- Data Import:
  This include bringing in data into SQL from different sources
  
- Data Cleaning and Preparation:
This includes handling duplicates, blank cells and text manipulation and extration using **`SQL COMMANDS`** such as;
1. DDL: **`CREATE`**, **`ALTER`**, **`DELETE`**, **`TRUNCATE`**.
2. DML: **`INSERT`**, **`UPDATE`**, **`DROP`**.
3. DQL: **`SELECT`** to fetch data.
4. TCL: **`ROLLBACK`**, **`COMMIT`**.
5. DCL: **`GRANT`**, **`REVOKE`**

- Data Analysis Techniques: This involve using analytical functions annd **`SQL CLAUSES`** such as **`WHERE`**, **`TOP`**, **`GROUPBY`**, **`ORDERBY`**, **`HAVING`** to derive insights from data. Functions include;
  **`SUM()`**, **`AVG()`**, **`MAX()`**,  **`MIN()`**, **`COUNT()`**.

```SQL
SELECT SUM(PROFIT)  as [TOTAL PROFIT HERO] FROM [dbo].[International Breweries]
WHERE COUNTRIES = 'NIGERIA' AND YEARS =2017 and brands= 'hero'
GROUP BY BRANDS
ORDER BY 1 DESC
```



