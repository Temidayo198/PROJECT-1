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

 - Data Summarization: create summaries using **`Pivot Tables`** making it easier to identify patterns or issues.

![IMG_3363](https://github.com/user-attachments/assets/83d0b45a-3893-4c5a-9612-9fd150a9553a)

![IMG_3364](https://github.com/user-attachments/assets/438c088c-b8bb-4f26-9ac9-68f52a4d76b8)

![IMG_3365](https://github.com/user-attachments/assets/cdc67063-3b5d-4a54-add6-a418619107a0)

![Screenshot (28)](https://github.com/user-attachments/assets/2557ace8-cc15-453b-8b23-e5faf3b6b6ad)

![IMG_3362](https://github.com/user-attachments/assets/0af50fd4-a907-449c-a3a5-de7a44095fa3)

![Screenshot (13)](https://github.com/user-attachments/assets/c3197177-3588-4e90-bf9e-74ba83e97f1d)

![Screenshot (12)](https://github.com/user-attachments/assets/1a802c4d-6887-48c2-af38-0391aafd36a6)


   




