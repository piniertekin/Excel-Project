# Bike Buyers Analysis

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Recommendations](#recommendations)

### Project Overview

This data analysis project on Excel aims to provide insights into the sales performance of a company's bike sales and the demographics of the buyers along with non-buyers. By analyzing various aspects of the demographics, we seek to identify trends, make data-driven recommendations, and gain a deeper understanding of the company's performance.

<img width="769" alt="Bike Sales Dashboard" src="https://github.com/piniertekin/excelproject/assets/155672246/0691bd8d-9ec9-417e-b1fd-4391cebaec2e">

### Data Sources

Sales Data: The primary dataset used for this analysis is the "Excel Project Dataset.xlsx" file, containing detailed information about buyers along with non-buyers.

### Sources

- Excel - data cleaning
- Excel - data analysis
- Excel - creating pivot tables, charts and the dashboard

### Data Cleaning/Preparation

In the initial data preparation phase, we performed the following tasks:

1. Data loading and inspection.
2. Removing duplicate values.
3. Data cleaning and formatting.

### Exploratory Data Analysis

Exploratory data analysis involved exploring the sales data to answer key questions, such as:

- What is the overall sales trend?
- Which age brackets are top buyers?
- What was the average income of the buyers?
- What was the customer commute distance?
  
<img width="667" alt="Customer Age Brackets" src="https://github.com/piniertekin/excelproject/assets/155672246/a3e4b2d4-ca10-49e9-a379-51383ceb2460">

### Data Analysis

Some interesting formulas/features we worked with

```excel
- =IF(L2>54,"Old",IF(L2>=31,"Middle Age",IF(L2<31,"Adolescent","Invalid")))

- Under "Row C - Gender", replacing all cells containing "M" with "Male", and all cells containing "F" with "Female" using ctrl + H

- Creating pivot tables and related pivot charts

- Creating a dashboard
```

### Results/Findings
The analysis results are summarized as follows:

1. The buyers of the company's bikes mostly consist of middle-aged customers, whereas under 31 year-olds and above 54 year-olds performed similarly, lagging behind middle-aged customers.
2. The average income of customers who bought bikes are hughed than those who have not, in both genders.
3. Average commute of the customers who overwhelmingly bought bikes is 0-1 miles.

### Recommendations

Based on the analysis, we recommend the following actions:

- Invest in discounts for customers with lower income to maximize revenue.
- Implement a marketing strategy to target customers under 31 years old and above 54 years old effectively.

### References

1. Excel
2. [GitHub](https://github.com/AlexTheAnalyst/Excel-Tutorial/blob/main/Excel%20Project%20Dataset.xlsx)

🚲 
💻 

