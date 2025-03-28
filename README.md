# Plant-Co-Performance-Analysis--Power-BI-Project-
## Project Overview 
This Power BI report provides a detailed analysis of the company's plant operations, focusing on gross profit (GP), quantity, and sales from 2022 to 2024.The goal of this project is to provide insightful visualizations of plant performance data, allowing managers to assess productivity, spot inefficiencies, and implement strategies to enhance operational efficiency.

## Business Questions
•How has our gross profit changed compared to last year?

•Which countries have experienced the largest decline in gross profit?

•What are the trends in gross profit changes throughout the year?

•Which product categories (Indoor, Landscape, Outdoor) are performing best?

•Which customer accounts contribute the most to revenue but have low profit margins?

•Are there any seasonal trends in gross profit?

•Which regions or product types should we focus on for growth opportunities?
## Process 

## Data Cleaning & Preparation
•Removed duplicates and null values.

•Standardized column names for consistency.

•Transformed date formats for accurate time-based analysis.
## Key Metrics
•	YTD (Year-to-Date):
The cumulative gross profit achieved up to the current point in the year.

•	PYTD (Previous Year-to-Date):
Gross profit achieved during the same time period in the previous year.

•	YTD vs PYTD:
The difference between YTD and PYTD values, showing the change in performance.
•	GP% (Gross Profit Percentage):
The gross profit margin percentage

## Data Analysis & Visualization 
1. YTD vs PYTD by Bottom 10 Countries
•	This treemap shows the gross profit change (YTD vs PYTD) for each country.
•	The size of the boxes represents the magnitude of the change, while the values show the actual change.
Example:
o	China: -405.00K (largest negative change).

2. YTD vs PYTD by Month (Waterfall Chart)
•	This chart visualizes monthly changes in gross profit compared to the previous year.
•	Green bars: Increase in gross profit.
•	Red bars: Decrease in gross profit.
•	The total bar shows the cumulative difference.
•	Can drill down to country and product to provide insights

3. YTD and PYTD by Quarter, Month, and Product Type (Stacked Column Chart)
•	Gross profit is segmented by quarter, month, and product type (Indoor, Landscape, Outdoor).
•	A yellow line indicates the values of PYTD over time.

4. Value YTD and GP% by Account (Scatter Plot)
•	Each data point represents a customer account.
•	X-axis: Value YTD (sales value).
•	Y-axis: GP% (gross profit percentage).
•	This chart helps identify accounts with high/low profit margins and sales values.

## Gross Profit Performance Analysis**

### **1. Overall Gross Profit Performance**
- YTD Gross Profit**: **$5.15M**  
- PYTD Gross Profit**: **$5.42M**  
- YTD vs PYTD Change**: **-265.29K**, indicating a **decrease in profitability** compared to last year.  
- Gross Profit Percentage (GP%)**: **39.62%**, which reflects the overall margin across all products and markets.  

### **2. Countries with the Largest Decline in Gross Profit**
  - China** had the highest decline in gross profit (-405K), followed by:  
  - Sweden **(-63.43K)**  
  - United Kingdom **(-57.38K)**  
  - Norway **(-51.81K)**  
  - France **(-50.35K)**  
- These countries might need a deeper analysis to determine the root cause of declining profits.  

### **3. Gross Profit Trend Over the Months**
- Highest Profit Month**: **December (~$0.5M YTD)**  
- Lowest Profit Month**: **February (~$0.33M YTD)**  
- Positive Recovery Trends** in March and April but followed by some declines in later months.  
- **Key Question**: What factors contributed to higher profitability in December and the decline in February?  

### **4. Product Type Analysis**
- **Indoor, Landscape, and Outdoor products** are compared across months.  
- **Indoor products** seem to have the **highest contribution to gross profit**.  
- Identifying which product categories underperformed compared to last year can help optimize product strategies.  

### **5. Customer Account Profitability Segmentation**
- The scatter plot suggests that some accounts contribute **high revenue but low profitability**.  
- This indicates a potential need to **optimize pricing, reduce costs, or focus on higher-margin customers**.  

### **Actionable Recommendations**
1. **Investigate China’s Performance**: Since China had the highest decline, analyze sales trends, pricing, and costs.  
2. **Understand Seasonal Variations**: Review why December had a peak and February had a dip—were there promotions, external factors, or demand shifts?  
3. **Optimize Low-Profit Accounts**: Consider renegotiating contracts or adjusting pricing strategies for accounts with low GP%.  
4. **Product Category Strategy**: If certain product types are underperforming, consider promotional strategies or cost reductions.  
5. **Country-Specific Actions**: Evaluate Sweden, UK, and Norway’s market conditions to identify improvement opportunities.
