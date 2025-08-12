# 📊 Sales Trend Analysis Using Aggregations

## 📌 Objective
The goal of this task is to **analyze monthly revenue and order volume** using SQL aggregate functions and date-based grouping.

## 🛠 Tools Used
- **MySQL** (can also work on PostgreSQL / SQLite)
- **Dataset**: `online_sales` table containing:
  - `order_date`
  - `amount`
  - `product_id`

## 📂 Dataset Overview
The dataset contains sales order records with their dates, amounts, and product details.  
We will use these fields to group and aggregate data by month and year.

## 📋 Steps Performed
1. **Connected to MySQL** and loaded the `online_sales` table.
2. **Extracted Month and Year** from `order_date` using:
   ```sql
   EXTRACT(MONTH FROM order_date) AS month
# TASK-6
