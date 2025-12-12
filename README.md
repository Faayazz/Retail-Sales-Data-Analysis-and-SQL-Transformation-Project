## 🛍️ Retail Sales Data Analysis and SQL Transformation Project

### 🌟 Overview
This project demonstrates the design and analysis of a retail sales database using SQL. It focuses on **data cleaning, transformation, and analytics** to simulate real-world business challenges.

The project highlights how SQL can handle messy datasets (nulls, duplicates, inconsistent formats) and generate robust business insights such as top-selling products, store revenue, return rates, and sales trends.

### 🎯 Problem Statement
In real businesses, raw data often contains missing values, duplicates, and inconsistent formats, making it unreliable for decision-making. The goal of this project was to:
* Build a relational retail database.
* Clean and standardize inconsistent data.
* Generate insights on sales performance, customer behavior, and returns.

### 🔍 Approach
#### Database Design
Created 5 interconnected tables: **Customers, Products, Orders, Order Items, and Returns**. 

#### Data Cleaning
Fixed null values, duplicates, and addressed **inconsistent date formats** across multiple tables to ensure data integrity.

#### Analysis & Insights
Generated actionable insights, including:
* Top/Bottom selling products (by quantity and revenue).
* Store-wise revenue and return counts.
* Monthly revenue trends.
* Overall return rate with detailed customer and product return breakdowns.

### 📊 Key Outcomes
* **✅ Clean Dataset:** Produced a reliable, standardized dataset ready for downstream analysis.
* **📈 Performance Insight:** Identified sales trends and top/bottom-performing stores and products.
* **🔄 Returns Management:** Calculated return rates and linked return reasons to specific customers and products.
* **🛒 Customer Behavior:** Revealed purchasing and return patterns.

### 🛠️ Tech Stack
* **SQL Dialect:** SQL Server (using functions like `TRY_CONVERT`, `MONTH()`, and `ROW_NUMBER()`).
* **SQL Concepts:** Joins, Aggregations, Window Functions, Common Table Expressions (CTEs), and complex Data Cleaning logic (`CASE` statements, `UPDATE` commands).

### 📂 Files in Repository
* `sales-data-analysis.sql` → Database schema creation, sample data insertion, and data cleaning queries.

### 🚀 Conclusion
This project demonstrates **end-to-end SQL skills**—from database creation and handling dirty data to advanced analytics—bridging the gap between raw data and actionable business intelligence.

---
