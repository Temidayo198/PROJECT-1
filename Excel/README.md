# Project Title: Sales Performance Analysis for a Retail Store

## Table of Contents
[Project Overview](#project-overview)

[Project Objectives](#project-objectives)

[Data Source](#data-source)

[Tool Used](#tool-used)

[Data Analysis Process](#data-analysis-process)


### Project Overview
---
This project aims to provide a comprehensive analysis of sales data for a retail store, identifying key insights to improve business strategies and drive sales growth. Through this analysis, we explore product performance, regional sales distribution, and monthly sales trends to uncover factors contributing to revenue and customer demand patterns.

### Project Objectives
- Summarize total sales by product, region, and month using pivot tables.
- Calculate average sales per product and total revenue by region.
- Generate additional reports to identify key insights

### Data Source
---
The dataset used for this analysis was provided by the course facilitator as part of the capstone project for data analysis training.

### Tool Used 
---
- Microsoft Excel [Download Here](https://www.microsoft.com)
  1. For Data Cleaning and Preparation
  2. For Analysis
 
###  Data Analysis Process
---

- Data Import:
The dataset was downloaded from the Canvas infrastructure and loaded into Excel for analysis.

- Data Cleaning and Preparation:
  1. Removed duplicate entries to ensure data accuracy.
  2. Cleared blank cells to prevent inconsistencies in calculations and summaries.

- Data Transformation: This involve structuring data into table by using **`ctrl+T`** shortcut

- Data Analysis Techniques: This involve using analytical functions to derive insights from data. Functions include;
  **`SUM`**, **`SUMIF`**, **`AVERAGE`**, **`MAXIFS`**, **`MINIFS`**, **`COUNT`**

  ```Excel
  |ORDER ID| CUSTOMER ID| PRODUCT | REGION | ORDER DATE | QUANTITY | UNIT PRICE | TOTAL SALES | 	          
  | 1001   | Cus1278    | Shirt   | North  | 1/31/2023  | 5        | 20         | 100         |
  | 1002   | Cus1022    | Shoe    | South  | 2/28/2023  | 10       | 50         | 500         |
  | 1003   | Cus1064    | Hat     | East   | 3/31/2023  | 7        | 15         | 105         |
  
  =MAXIFS(hi,D:D, "North")
  =MINIFS(hi,D:D,"North")
  =AVERAGE(hi)
  ```

 




