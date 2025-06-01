# 🛒 E-commerce Data Analysis using SQL

## 📌 Project Overview

This project demonstrates how to perform SQL-based data analysis on a sample e-commerce dataset. It involves creating a relational database, inserting sample customer and order data, and writing various SQL queries to extract insights.

---

## 🎯 Objective

To analyze e-commerce data using SQL by:
- Creating a database schema
- Inserting relevant data
- Applying SQL queries like SELECT, JOIN, GROUP BY, subqueries, views, and indexes

---

## 🛠 Tools Used

- MySQL (Server + CLI / Workbench)
- Any SQL-compatible RDBMS will also work (PostgreSQL, SQLite, etc.)

---

## 📁 Database Schema

### 📦 Tables:
- `customers (customer_id, name, city)`
- `orders (order_id, customer_id, amount)`

### 🔗 Relationships:
- `orders.customer_id` → Foreign Key referencing `customers.customer_id`

---

## 💾 Sample Data

```sql
-- Customers
INSERT INTO customers VALUES 
(1, 'Alice', 'New York'), 
(2, 'Bob', 'Los Angeles'),
(3, 'Charlie', 'New York');

-- Orders
INSERT INTO orders VALUES 
(101, 1, 500.00),
(102, 1, 700.00),
(103, 2, 300.00);
