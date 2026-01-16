# supermarket-dashboard
This project involves a comprehensive analysis of supermarket sales data across different customer segments and geographical locations. The goal is to provide actionable insights into profitability, sales trends, and customer behavior using interactive visualizations.

## dataset used
- <a href=  "https://github.com/mohamed231177/supermarket-dashboard/blob/main/Sample%20-%20Superstore.csv"> dataset</a>
##  Questions (KPIs)
- What is the total revenue and net profit achieved?
- What is the total volume of products sold (Quantity)?
- What is the overall average discount rate applied across all orders?
- Which customer segment contributes the most to the total quantity sold?
- What is the historical trend of profit from 2014 to 2017?
- Which categories and sub-categories generate the highest sales volume?

- dashboard interaction <a href=  "https://github.com/mohamed231177/supermarket-dashboard/commit/dbb2ddb7ffa1b9c89e6ad9ff703d6e2c798442a7">view dahboard </a>

## process 

- Data Cleaning & ETL: Performed extensive data cleaning to handle missing values and "Blank" sub-categories while ensuring data type consistency.
- Data Modeling (Star Schema): Designed a robust Star Schema by separating the dataset into:
Fact Table: Containing transactional data (Sales, Profit, Quantity, Discounts).
Dimension Tables: Creating specialized tables for Products, Customers, Geography, and Calendar.
- DAX Calculations Developed custom DAX measures
  

## dashboard 
<img width="1741" height="731" alt="page 1" src="https://github.com/user-attachments/assets/974bae40-1c2b-4bad-93b7-f53b134835bc" />
<img width="1740" height="736" alt="page 2" src="https://github.com/user-attachments/assets/e1b6e805-5d68-403e-b6ad-ec84067e340e" />

## Final Conclusion 
- Overall Business Health: The supermarket achieved a healthy total profit of $286.40K on $2M in sales, indicating a stable profit margin despite significant market competition.

- Customer Dominance: The Consumer Segment is the core driver of the business, contributing to over 51% of the total quantity sold, making it the most critical area for marketing focus.

- Seasonality Insights: Profit trends from 2014 to 2017 reveal consistent growth and cyclical peaks, suggesting that inventory and staffing should be optimized for high-demand year-end periods





