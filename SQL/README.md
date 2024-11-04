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
  2. For Analysis

  ###  Data Analysis Process
---

- Data Import:
  To prepare the data for analysis in the SQL environment, the original dataset was converted from Excel to a CSV (Comma-Separated Values) format. This format transformation ensured compatibility and ease of import into SQL, allowing for efficient data querying and manipulation.
  
- Data Analysis Techniques: This involve using analytical functions and **`SQL CLAUSES`** such as **`WHERE`**, **`TOP`**, **`GROUPBY`**, **`ORDERBY`** to derive insights from data. Functions include;
  **`SUM()`**, **`AVG()`**,  **`COUNT()`**.

```SQL
Select Product, sum([Total_Sales]) as Total_SalesbyProduct from [dbo].[LITA Capstone Dataset (1) CSV]
where Product is not null
group by product order by Total_SalesbyProduct

```



