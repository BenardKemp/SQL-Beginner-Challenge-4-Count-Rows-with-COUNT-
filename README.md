# SQL Beginner Challenge #4: Count Rows with COUNT()

**Difficulty:** Beginner  
**Estimated time:** 5–10 minutes  
**Concepts:** `COUNT()`, aggregate functions, counting rows  

This challenge introduces how to count records in a table using the `COUNT()` function—a core skill in reporting and analytics.

---

## 🧠 The Problem

A product manager asks a simple question:

> “How many products do we have in our catalog?”

Instead of listing rows, you need to return a **single number** representing the total count of products.

---

## 📊 Table Schema

### `products`

| Column Name | Type      | Description |
|------------|-----------|-------------|
| product_id | INTEGER   | Unique product ID |
| name       | TEXT      | Product name |
| category   | TEXT      | Product category |
| price      | DECIMAL   | Product price |
| stock_qty | INTEGER   | Units in stock |
| created_at | TIMESTAMP | Creation timestamp |

---

## 🧪 Sample Data

| product_id | name                 | category     | price  |
|-----------:|----------------------|--------------|-------:|
| 101 | Wireless Mouse      | Accessories | 24.99 |
| 102 | Mechanical Keyboard | Accessories | 89.00 |
| 103 | 27-inch Monitor     | Displays    | 229.99 |
| 104 | USB-C Hub           | Accessories | 34.50 |
| 105 | Laptop Stand        | Workspace   | 39.99 |

---

## ✅ Requirements

Your query must:

- Count all rows in the `products` table
- Use the `COUNT()` function
- Return a single row with a single column
- Name the output column `total_products`

---

## ✍️ Your Task

Write a SQL query that fulfills the requirements.

```sql
-- Write your query here

