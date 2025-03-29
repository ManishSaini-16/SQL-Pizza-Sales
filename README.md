# 🍕 Pizza Sales Analysis

## 📌 Overview
This project analyzes pizza sales data using SQL queries to extract key business insights. The dataset contains order details, pizza types, and sales transactions, helping to understand sales trends, customer preferences, and revenue distribution.

## 📊 Key Insights Extracted

### 1️⃣ Sales & Order Trends
- **Total Orders:** Retrieve the total number of orders placed.
- **Total Revenue:** Calculate the total revenue generated from pizza sales.
- **Order Distribution by Hour:** Identify peak order hours to optimize operations.
- **Average Pizzas Ordered per Day:** Group orders by date and calculate daily trends.

### 2️⃣ Best-Selling & High-Value Items
- **Highest-Priced Pizza:** Identify the most expensive pizza available.
- **Most Common Pizza Size:** Determine the most popular pizza size among customers.
- **Top 5 Most Ordered Pizza Types:** Rank pizza types based on total orders.

### 3️⃣ Category-Wise Sales Insights
- **Total Quantity per Category:** Analyze the demand for each pizza category.
- **Category-Wise Distribution:** Identify the proportion of different pizza categories.

### 4️⃣ Revenue Performance & Growth
- **Top 3 Pizzas by Revenue:** Determine the highest revenue-generating pizzas.
- **Revenue Contribution by Category:** Analyze each category's percentage contribution to total revenue.
- **Cumulative Revenue Over Time:** Track revenue growth and trends.
- **Top 3 Pizzas by Category (Revenue-Based):** Identify the best-performing pizzas within each category.

## 🔍 SQL Queries Used
- **Aggregations:** `SUM()`, `COUNT()`, `AVG()`, `ROUND()`
- **Joins:** `INNER JOIN` for combining multiple tables
- **Filtering & Sorting:** `ORDER BY`, `LIMIT`
- **Window Functions:** `SUM() OVER()`, `RANK() OVER(PARTITION BY ...)`
