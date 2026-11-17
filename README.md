# 🍕 Pizza Sales Analysis Using SQL

## 📌 Project Overview

This project focuses on analyzing pizza sales data using **MySQL** to identify sales trends, customer ordering patterns, product performance, and revenue insights.

The objective is to transform raw sales data into meaningful business insights by writing SQL queries that help understand which pizzas generate the highest revenue, which categories are most popular, and when customers place the most orders.

The project demonstrates practical SQL skills, including data aggregation, multi-table joins, subqueries, Common Table Expressions concepts, window functions, ranking, and business-oriented data analysis.

## 🎯 Business Objectives

The key objectives of this project are:

- Analyze overall sales performance and revenue generation.
- Identify the most popular pizza types and sizes.
- Understand category-wise sales distribution.
- Determine peak ordering hours.
- Identify top-performing pizzas based on revenue.
- Analyze daily sales trends and cumulative revenue.
- Evaluate the revenue contribution of different pizza categories.
- Generate insights that can support business and sales decisions.

## 🛠️ Tools & Technologies

- **Database:** MySQL
- **Query Language:** SQL
- **IDE:** MySQL Workbench
- **Dataset Format:** CSV

## 📂 Dataset Description

The project uses four datasets containing pizza sales information.

| Dataset | Description |
|---|---|
| `orders.csv` | Contains order IDs, order dates, and order times. |
| `order_details.csv` | Contains order details, pizza IDs, and quantities. |
| `pizzas.csv` | Contains pizza IDs, sizes, pizza types, and prices. |
| `pizza_types.csv` | Contains pizza names, categories, and related information. |

### Database Schema

The project uses four interconnected tables:

1. **orders** – Stores order-level information.
2. **order_details** – Stores individual pizza order details and quantities.
3. **pizzas** – Stores pizza size, type, and pricing information.
4. **pizza_types** – Stores pizza names and category information.

## 📊 SQL Analysis & Business Questions

The project covers 13 SQL analysis questions, divided into business-focused areas.

### 1. Sales Performance Analysis

- Calculate the total number of orders placed.
- Calculate the total revenue generated from pizza sales.
- Calculate the average number of pizzas ordered per day.
- Analyze cumulative revenue generated over time.

### 2. Product Performance Analysis

- Identify the highest-priced pizza.
- Identify the most commonly ordered pizza size.
- Find the top 5 most ordered pizza types based on quantity.
- Identify the top 3 pizza types based on revenue.

### 3. Category Analysis

- Calculate the total quantity of pizzas ordered in each category.
- Analyze the category-wise distribution of pizzas.
- Calculate the percentage contribution of each pizza category to total revenue.
- Identify the top 3 highest-revenue pizza types within each category.

### 4. Order Pattern Analysis

- Analyze the distribution of orders by hour of the day.
- Identify customer ordering patterns based on order timings.

## 💡 SQL Concepts Applied

The following SQL concepts are implemented throughout the project:

- SELECT, WHERE, ORDER BY
- GROUP BY and HAVING
- Aggregate Functions (SUM, COUNT, AVG)
- INNER JOIN and Multiple Table Joins
- Subqueries
- Window Functions
- RANK() and PARTITION BY
- Date and Time Functions
- ROUND() and Mathematical Operations
- Revenue and Percentage Calculations

## 📈 Business Value

The analysis helps answer important business questions:

- Which pizza products contribute the most to revenue?
- Which pizza categories have the highest demand?
- Which pizza sizes are ordered most frequently?
- During which hours are orders concentrated?
- Which products should receive more business attention?
- How does revenue accumulate over time?

These insights can help pizza businesses understand product demand, evaluate sales performance, and make more informed operational and marketing decisions.


## 📁 Project Structure

```text
Pizza-Sales-Analysis-SQL/
│
├── Pizza.sql
│
├── orders.csv
├── order_details.csv
├── pizzas.csv
├── pizza_types.csv
│
└── README.md
```

## 🎓 Key Learnings

Through this project, I gained practical experience in:

- Writing SQL queries to solve real-world business problems.
- Working with relational databases and multiple-table joins.
- Performing sales and revenue analysis.
- Applying aggregate and window functions.
- Translating business questions into SQL queries.
- Extracting meaningful insights from structured datasets.

## 👨‍💻 Author

**Vedant Akhade**


⭐ If you find this project useful, feel free to explore the SQL queries and datasets.


