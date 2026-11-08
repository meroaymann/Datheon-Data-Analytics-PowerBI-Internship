# Superstore Retail Sales | Exploratory Data Analysis (EDA)

### Datheon Data Analytics & Power BI Internship | Task 1

**Author:** Amira Ayman  
**Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn, Google Colab  
**Project Type:** Data Analytics, Exploratory Data Analysis, Business Insights

---

## Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on the Superstore Retail Sales dataset as part of the Datheon Data Analytics & Power BI Internship.

The analysis explores sales performance, profitability, customer purchasing behavior, seasonal trends, and discount sensitivity to identify meaningful business patterns and opportunities for improvement.

The objective is to transform raw retail transaction data into clear, actionable insights through data cleaning, statistical analysis, and visualizations.

## Project Objectives

- Clean and preprocess the dataset to ensure data quality and consistency.
- Identify and handle missing values, duplicates, and incorrect data types.
- Analyze overall sales, profit, and key business performance indicators.
- Compare revenue and profitability across product categories, regions, and customer segments.
- Investigate monthly sales trends and seasonal patterns.
- Examine the relationship between discount levels and profitability.
- Analyze customer purchase volume, spending, and frequency.
- Identify high-performing and underperforming product subcategories.
- Present executive business findings and recommendations.

## Dataset Information

**Dataset:** Superstore Retail Sales  
**Source:** [Datheon Superstore Sales Dataset](https://www.datheon.in/datasets/superstore_sales.csv)

| Metric | Value |
|---|---|
| Original Records | 10,800 |
| Cleaned Records | 9,994 |
| Unique Orders | 5,009 |
| Unique Customers | 793 |
| Analysis Period | 2015–2018 |
| Missing Values After Cleaning | 0 |
| Exact Duplicate Rows After Cleaning | 0 |

### Data Cleaning

The dataset was cleaned and prepared for analysis using Pandas.

The preprocessing steps included:

- Inspecting dataset structure, data types, and missing values.
- Removing 806 incomplete records.
- Checking for exact duplicate records and duplicate row identifiers.
- Replacing 11 missing postal codes associated with Burlington, Vermont, with `Unknown` rather than assigning unverified values.
- Converting date columns into appropriate datetime formats.
- Creating additional date features for monthly and yearly analysis.
- Validating the cleaned dataset before performing exploratory analysis.

## Tools and Technologies

| Tool | Purpose |
|---|---|
| Python | Data processing and analysis |
| Pandas | Data cleaning, manipulation, and aggregation |
| NumPy | Numerical calculations and validation |
| Matplotlib | Data visualization |
| Seaborn | Statistical and business visualizations |
| Google Colab | Notebook development and execution |
| GitHub | Project documentation and version control |

## Exploratory Data Analysis

The project covers the following analytical areas:

1. **Data Cleaning and Quality Assessment:** Inspecting and preparing the dataset.
2. **Overall Business Performance:** Calculating sales, profit, profit margin, order volume, and average order value.
3. **Category Analysis:** Comparing sales and profitability across Technology, Furniture, and Office Supplies.
4. **Regional Analysis:** Evaluating business performance across geographic regions.
5. **Customer Segment Analysis:** Comparing Consumer, Corporate, and Home Office customers.
6. **Monthly Sales Analysis:** Exploring sales trends and seasonal patterns.
7. **Discount Sensitivity:** Investigating the relationship between discounts, profit margins, and loss-making transactions.
8. **Subcategory Analysis:** Identifying the most and least profitable product subcategories.
9. **Top Customer Analysis:** Examining customer spending and profitability.
10. **Purchase Frequency Analysis:** Understanding customer order frequency.
11. **Data Validation:** Checking the consistency of calculated results.

## Key Performance Indicators

| KPI | Result |
|---|---:|
| Total Sales | $2,297,200.86 |
| Total Profit | $286,397.02 |
| Overall Profit Margin | 12.47% |
| Total Orders | 5,009 |
| Unique Customers | 793 |
| Units Sold | 37,873 |
| Average Order Value | $458.61 |

The business generated approximately **$2.30 million in sales** and **$286.40 thousand in profit**, achieving an overall profit margin of 12.47%.

## Key Business Findings

### 1. Technology Is the Most Profitable Category

Technology generated the highest category revenue at **$836,154.03** and the highest total profit at **$145,454.95**, achieving a profit margin of 17.40%.

Furniture generated $741,999.80 in sales but only $18,451.27 in profit, resulting in a considerably lower margin of 2.49%.

**Business Recommendation:** Prioritize profitable Technology products while investigating pricing, discounting, and cost structures within Furniture.

### 2. The West Region Leads in Sales and Profitability

The West region recorded the highest sales at **$725,457.82** and the highest total profit at **$108,418.45**, with a profit margin of 14.94%.

The Central region generated $501,239.89 in sales but achieved the lowest regional profit margin at 7.92%.

**Business Recommendation:** Investigate the factors associated with stronger profitability in the West and identify opportunities to improve margins in the Central region.

### 3. Consumer Customers Generate the Highest Revenue

The Consumer segment generated **$1,161,401.34 in sales**, making it the largest customer segment by revenue.

However, the Home Office segment achieved the highest profit margin at 14.03%, compared with 13.03% for Corporate and 11.55% for Consumer customers.

**Business Recommendation:** Maintain strong engagement with Consumer customers while exploring profitable growth opportunities in the Home Office segment.

### 4. Sales Exhibit Strong Seasonal Patterns

Sales activity was particularly strong during September, November, and December.

November recorded the highest average monthly sales at **$88,115.27**, followed by December at $81,323.38 and September at $76,912.49.

February recorded the lowest average monthly sales at $14,937.81.

**Business Recommendation:** Use historical seasonal patterns to support inventory planning, marketing campaigns, and operational resource allocation during high-demand periods.

### 5. Higher Discounts Are Associated With Lower Profitability

Transactions without discounts achieved a profit margin of **29.51%**.

At a 20% discount, the aggregate profit margin was 11.82%. At a 30% discount, the margin declined to -10.05%.

All recorded sales lines at discount levels of 50%, 60%, 70%, and 80% generated losses.

**Business Recommendation:** Review discount policies, particularly for discounts of 30% or higher, and evaluate profitability before approving substantial discounts.

These results indicate an observed association between discounts and profitability, not a proven causal relationship.

### 6. Tables and Bookcases Reduce Furniture Profitability

Tables generated **$17,725.48 in losses**, making them the least profitable subcategory.

Bookcases also recorded losses of $3,472.56.

In contrast, Copiers generated the highest total profit among all subcategories at $55,617.82.

**Business Recommendation:** Review the pricing, costs, and discount strategies for Tables and Bookcases while identifying opportunities to strengthen profitable product lines.

### 7. High Customer Revenue Does Not Always Mean High Profit

Sean Miller generated the highest individual customer revenue at **$25,043.05**, but his purchases resulted in a net loss of $1,980.74.

In comparison, Tamara Chand generated $19,052.22 in sales and $8,981.32 in profit.

**Business Recommendation:** Evaluate customer performance using both revenue and profitability rather than relying exclusively on total spending.

### 8. Repeat Purchasing Is Common Among Customers

Customers placed an average of **6.32 orders**, with a median of 6 orders during the analysis period.

Approximately **98.49% of customers placed more than one order**, while only 1.51% placed a single order.

The most common purchase frequency was five orders per customer.

**Business Recommendation:** Investigate repeat purchasing patterns and consider customer engagement strategies based on purchase frequency, spending, and profitability.

This analysis measures repeat purchasing within the dataset and does not establish formal customer retention rates.

## Business Recommendations

Based on the exploratory analysis, the following actions are recommended:

1. **Improve discount management:** Review high-discount transactions and establish profitability checks before approving substantial discounts.
2. **Address underperforming products:** Investigate losses associated with Tables and Bookcases.
3. **Strengthen regional profitability:** Examine opportunities to improve profit margins in the Central region.
4. **Optimize seasonal planning:** Use historical monthly sales patterns to inform inventory, staffing, and marketing decisions.
5. **Focus on profitable customer relationships:** Evaluate customers based on both revenue and profit contributions.
6. **Support profitable product categories:** Explore opportunities to grow high-margin product lines.
7. **Analyze repeat purchasing behavior:** Investigate customer purchasing frequency to support future engagement strategies.

## Data Validation

Final validation checks were performed to confirm the consistency of the analytical results.

The validation confirmed that:

- Total sales matched across category, region, segment, and monthly aggregations.
- Total profit matched across category, region, and segment aggregations.
- The customer analysis included all 793 unique customers.
- The purchase frequency distribution accounted for all 793 customers.
- The cleaned dataset contained no remaining missing values.
- The cleaned dataset contained no exact duplicate rows.

All implemented validation checks passed successfully.

## How to Run the Project

1. Clone or download this GitHub repository.
2. Open `Datheon_Task1_Superstore_EDA.ipynb` in Google Colab or Jupyter Notebook.
3. Install the required Python libraries if they are not already available.
4. Download the dataset from the source link provided above.
5. Upload the dataset or configure its path as required by the notebook.
6. Execute the notebook cells sequentially to reproduce the analysis and visualizations.

### Required Python Libraries

```bash
pip install pandas numpy matplotlib seaborn
```

## Project Deliverables

- **Jupyter Notebook:** `Datheon_Task1_Superstore_EDA.ipynb`
- Data cleaning and preprocessing workflow
- Descriptive statistics and business KPIs
- Exploratory analysis and visualizations
- Customer purchase frequency and discount sensitivity analysis
- Eight executive business findings
- Business recommendations
- Final data validation

## Limitations

- The analysis is based on historical transactions from 2015 to 2018.
- The findings describe observed patterns and relationships rather than establishing causation.
- Seasonal observations are based on four years of historical data and may not represent future demand.
- Customer purchase frequency does not directly measure customer retention.
- Recommendations should be evaluated further before business implementation.

## Conclusion

This project demonstrates how Exploratory Data Analysis can be used to understand retail business performance and identify opportunities for improvement.

The analysis revealed meaningful differences in sales, profitability, customer purchasing behavior, seasonal demand, and discount sensitivity.

Although the business generated more than $2.29 million in revenue, profitability varied significantly across categories, regions, products, and customers.

The findings highlight the importance of evaluating profitability alongside revenue and demonstrate how data-driven insights can support business decision-making.

---

**Datheon Data Analytics & Power BI Internship**  
**Task 1: Exploratory Data Analysis on Superstore Retail Sales**  
**Developed by Amira Ayman**
