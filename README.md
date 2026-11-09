# 🍕 Pizza Hut Sales Analysis | SQL Project

Analysis of Pizza Hut sales data using MySQL. I answered 13 business questions on orders, revenue, pizza popularity and peak hours, using joins, aggregations, subqueries and window functions.

## 📊 Key Numbers
- **Total orders:** 21,350
- **Total revenue:** $817,860.05
- **Average pizzas sold per day:** about 138

## 🗂️ Database Tables
- `orders` (order_id, order_date, order_time)
- `order_details` (order_details_id, order_id, pizza_id, quantity)
- `pizzas` (pizza_id, pizza_type_id, size, price)
- `pizza_types` (pizza_type_id, name, category, ingredients)

## ❓ Questions Solved
1. Total number of orders placed
2. Total revenue from pizza sales
3. Highest-priced pizza
4. Most common pizza size ordered
5. Top 5 most ordered pizza types
6. Total quantity by pizza category
7. Orders by hour of the day
8. Category-wise distribution of pizzas
9. Average pizzas ordered per day
10. Top 3 pizza types by revenue
11. Revenue contribution by category (%)
12. Cumulative revenue over time
13. Top 3 pizza types by revenue in each category

## 💡 Key Findings
- The Greek Pizza is the highest-priced item at $35.95.
- Large (L) is the most popular size (about 38% of orders).
- Peak order hours are 12 PM to 1 PM and 5 PM to 7 PM.
- The Thai Chicken Pizza earns the most revenue ($43,434.25).
- Classic is the top category by quantity sold (14,888 pizzas) and by revenue share (26.91%).

## 🛠️ SQL Concepts Used
JOINs, GROUP BY, ORDER BY, LIMIT, aggregate functions (SUM, COUNT, AVG, ROUND), date and time functions (HOUR), subqueries, window functions (SUM OVER, RANK OVER, PARTITION BY)

## 📁 Files in this Repository
- `SQL_Pizzahut_Project_Formatted.sql` : all 13 queries
- `Pizza_Hut_SQL_Project_v3.pdf` : full report with queries, results and insights

## 🧰 Tools
MySQL, MySQL Workbench

## 👤 Author
Your Name | LinkedIn: add your profile link here
