# Datheon-Data-Analytics-PowerBI-Internship
# Superstore Retail Sales | Exploratory Data Analysis (EDA)

### Datheon Data Analytics & Power BI Internship | Task 1

**Author:** Amira Ayman  
**Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn, Google Colab

## Project Overview

This project explores the Superstore Retail Sales dataset to analyze business performance, customer purchasing behavior, sales seasonality, and the relationship between discounts and profitability.

The goal is to transform raw retail data into meaningful insights through data cleaning, statistical analysis, and visualization, helping identify business strengths, financial risks, and opportunities for improvement.

## Project Objectives

- Clean and preprocess raw retail sales data.
- Identify missing values, duplicates, and data quality issues.
- Analyze sales and profitability across product categories, regions, and customer segments.
- Explore monthly sales trends and seasonal patterns.
- Investigate discount sensitivity and its relationship with profit.
- Analyze customer purchase volume and frequency.
- Identify high-performing and underperforming product subcategories.
- Provide actionable business insights and recommendations.

## Dataset Information

**Dataset:** Superstore Retail Sales  
**Source:** [Datheon Superstore Dataset](https://www.datheon.in/datasets/superstore_sales.csv)

| Metric | Value |
|---|---|
| Original Records | 10,800 |
| Cleaned Records | 9,994 |
| Unique Orders | 5,009 |
| Unique Customers | 793 |
| Analysis Period | 2015–2018 |
| Missing Values After Cleaning | 0 |
| Exact Duplicate Rows After Cleaning | 0 |

During preprocessing, 806 incomplete records were excluded. Eleven missing postal codes associated with Burlington, Vermont, were labeled `Unknown`.

## Tools and Technologies

- **Python:** Data analysis and processing
- **Pandas:** Data cleaning, manipulation, and aggregation
- **NumPy:** Numerical operations and validation
- **Matplotlib:** Statistical and business visualizations
- **Seaborn:** Data visualization
- **Google Colab:** Notebook development and execution
- **GitHub:** Version control and project documentation

## Exploratory Data Analysis

The project covers the following analytical areas:

1. Data Cleaning and Quality Assessment
2. Overall Sales Performance and Business KPIs
3. Sales and Profit by Product Category
4. Regional Sales and Profitability
5. Customer Segment Analysis
6. Monthly Sales Trends and Seasonality
7. Discount Sensitivity and Profitability
8. Product Subcategory Performance
9. Top Customers by Revenue
10. Customer Purchase Frequency
11. Final Data Validation

## Key Performance Indicators

| KPI | Result |
|---|---:|
| Total Sales | $2,297,200.86 |
| Total Profit | $286,397.02 |
| Profit Margin | 12.47% |
| Total Orders | 5,009 |
| Total Customers | 793 |
| Units Sold | 37,873 |
| Average Order Value | $458.61 |

## Key Business Findings

### 1. Technology Leads in Profitability

Technology generated $836,154.03 in sales and $145,454.95 in profit, achieving a 17.40% profit margin.

Furniture generated substantial revenue but achieved a significantly lower profit margin of 2.49%.

### 2. West Is the Strongest Performing Region

The West region generated $725,457.82 in sales and $108,418.45 in profit, with a 14.94% profit margin.

The Central region recorded the lowest regional profit margin at 7.92%.

### 3. Consumer Customers Generate the Most Revenue

The Consumer segment contributed $1,161,401.34 in sales.

However, Home Office customers achieved the highest segment profit margin at 14.03%.

### 4. Sales Exhibit Seasonal Patterns

November recorded the highest average monthly sales at $88,115.27, followed by December and September.

February consistently represented a relatively low-sales period, with the lowest average monthly sales across the four years.

### 5. Higher Discounts Are Associated With Lower Profitability

Transactions without discounts achieved a 29.51% profit margin.

At a 30% discount, the aggregate profit margin declined to -10.05%. Higher discount levels were frequently associated with losses.

This is an observed relationship and does not establish causation.

### 6. Tables and Bookcases Reduce Furniture Profitability

Tables generated losses of $17,725.48, while Bookcases recorded losses of $3,472.56.

Copiers were the most profitable subcategory, generating $55,617.82 in profit.

### 7. High Revenue Does Not Guarantee High Customer Profitability

Sean Miller generated the highest customer revenue at $25,043.05 but recorded an overall loss of $1,980.74.

This demonstrates the importance of evaluating customer profitability alongside revenue.

### 8. Repeat Purchasing Is Common

Customers placed an average of 6.32 orders during the analysis period.

Approximately 
