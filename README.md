# task6
# 📊 Task 6 – Sales Trend Analysis Using Aggregations

## 🎯 Objective
Analyze monthly revenue and order volume using SQL aggregation functions.

## 🛠 Tools Used
- MySQL / PostgreSQL / SQLite
- GitHub

## 📂 Dataset
Table: online_sales  
Columns used:
- order_id
- order_date
- amount
- product_id

## 🔎 Analysis Performed

### 1️⃣ Monthly Revenue and Order Volume
- Used EXTRACT() to get year and month
- Used SUM(amount) to calculate revenue
- Used COUNT(DISTINCT order_id) to calculate order volume
- Grouped using GROUP BY year and month

### 2️⃣ Revenue for Specific Year
- Filtered data using WHERE clause
- Aggregated monthly sales

### 3️⃣ Top 3 Months by Revenue
- Ordered by total revenue in descending order
- Limited results using LIMIT 3

## 📈 Key Findings
- Revenue trends vary across months.
- Some months show peak sales performance.
- Order volume and revenue trends are correlated.

## 📚 Concepts Learned
- GROUP BY
- ORDER BY
- SUM()
- COUNT(DISTINCT)
- Aggregate functions
- Handling NULL values
- Time-based data analysis

## ✅ Conclusion
This task helped in understanding how to analyze time-based sales data using SQL aggregation techniques.
