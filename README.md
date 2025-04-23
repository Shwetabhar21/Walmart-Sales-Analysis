## 🛒 Walmart Sales Analysis

This project analyzes sales data from Walmart to identify trends, especially around holiday periods. It uses SQL queries to explore patterns and generate insights from the dataset.

## 📁 Project Structure

- `Walmart_sales_analysis.sql` — The core SQL script containing:
  - Monthly trend analysis of sales.
  - Comparison of weekly sales performance before, during, and after holidays using window functions (`LAG`, `LEAD`).
  - Use of Common Table Expressions (CTEs) for modular query building.

## 📊 Key Insights

- Monthly trends in total weekly sales across all stores.
- Impact of holidays on sales performance using comparative analysis of weeks surrounding holidays.

## 🛠️ Tools Used

- SQL (MySQL 8.0+)
- CTEs (Common Table Expressions)
- Window functions (`LAG`, `LEAD`)
- Aggregations and date formatting

## 📌 Requirements

- MySQL 8.0 or later (CTE and window function support required)
- Walmart dataset in a table named `walmart` with the following columns:
  - `Store`
  - `Date`
  - `Weekly_Sales`
  - `Holiday_Flag`
  - `Temperature`
  - `Fuel_Price`
  - `CPI`
  - `Unemployment`

## 📈 How to Use

1. Import your Walmart dataset into a MySQL database.
2. Execute the SQL script in your MySQL Workbench or any compatible environment.
3. Review the output for sales trends and holiday insights.
