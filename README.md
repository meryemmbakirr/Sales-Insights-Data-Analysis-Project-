# Sales Insights Data Analysis Project

## About This Project

This project was completed as a hands-on learning exercise to strengthen my practical skills in **MySQL** and **Power BI**, following a structured video tutorial and then extending the analysis with my own queries and dashboard design choices. My goal was not just to follow along, but to genuinely understand how relational databases and BI tools work together to turn raw sales data into actionable business insights.

The project uses a sample sales dataset (customers, transactions, products, markets, and date dimension tables) to analyze revenue performance across different regions, time periods, and customer segments.

## What I Learned

**Database Setup & SQL**
- Installed and configured a local MySQL server, and imported a relational database from a SQL dump file
- Wrote SQL queries involving filtering (`WHERE`), pattern-based selection, and `DISTINCT` values
- Used `INNER JOIN` to combine transaction data with a date dimension table for time-based analysis
- Applied aggregate functions (`SUM`, `COUNT`) to calculate total revenue and customer counts
- Combined multiple conditions (`AND` / `OR`) to answer specific business questions, such as regional revenue by month and year

**Power BI & Data Visualization**
- Built an end-to-end interactive dashboard from a relational data model with multiple connected tables
- Used **Power Query (M language)** to create custom calculated columns, including currency normalization logic (converting USD to a base currency)
- Designed KPI cards, trend charts, and ranked bar charts (Top 5 Customers, Top 5 Products, Revenue by Market)
- Implemented slicers for dynamic, interactive filtering by year and month

## Dashboard Preview

*(dashboard screenshot goes here — e.g. `![Dashboard](dashboard.png)`)*

## Tools Used
`MySQL` `Power BI` `Power Query (M)` `SQL`

## Reference
This project follows the tutorial series by [Codebasics](https://www.youtube.com/watch?v=WuBcTJnIuzo), adapted and extended with my own queries and dashboard layout.
