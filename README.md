#   Brazilian Olist E-Commerce Analysis (SQL Project)

This project showcases an end-to-end SQL analysis of the **Brazilian Olist E-commerce dataset**, covering customer behavior, order performance, revenue insights, delivery efficiency, and product category trends.

---

## **Project Overview**

This project analyzes Brazilian e-commerce performance using SQL on the **Olist** dataset.
The workflow includes **data cleaning**, **schema correction**, **date formatting**, and **KPI calculations** using multiple SQL queries.
The goal is to understand **customer behavior**, **order performance**, **delivery timelines**, **product trends**, and **seller performance**.

---

## **Dataset Files (9 CSV Files)**

All raw datasets from the official Olist E-Commerce repository, including customers, sellers, products, orders, order items, payments, reviews, geolocation, and category translations.

---

## ** Data Cleaning & Preprocessing (SQL)**

Performed using **olist_sql_script.sql**, including:

* Fixing corrupted/BOM column names
* Standardizing column data types
* Correcting date and datetime formats
* Cleaning product category names
* Ensuring consistent primary keys across tables

---

## **Key Insights (From SQL KPI Queries)**

Generated using **OLIST_KPI_SQL_QUERIES.sql**, including:

* **Unique Customers** (distinct buyers)
* **Total Sales** (from order_items)
* **Delivered Orders** count
* **Average Order Value (AOV)**
* **Total Revenue**
* **Weekend vs Weekday payment trends**
* **Impact of review score on delivery days**
* **Top-selling product categories**
* **Monthly sales trends by category**
* **Top sellers (revenue & product count)**
* **Average delivery time**
* **Payment method distribution**
* **Top 10 cities by sales**

These insights highlight purchase behavior, product demand, delivery performance, and seller contribution.

---

## **Main Analysis Covered**

* Customer growth & order trends
* Revenue and payment insights
* Delivery time & logistics performance
* Review score correlation with shipping days
* Product category performance
* Monthly & city-wise sales patterns
* Seller-level contribution
* Average Order Value (AOV)
* Payment method trends

---

## **Tools Used**

* **MySQL** – Data cleaning, modeling, calculations
* **SQL** – Joins, CTEs, date/time functions, aggregations
* **Olist E-commerce Dataset (Brazil)**

---

## **How to Use**

1. Import all **9 CSV files** into a SQL database (e.g.MySQL).
- Download: **[Olist Dataset](https://drive.google.com/drive/folders/1xSGPZ0LX4a80hLVp_el5s1invOJJ8OqR?usp=drive_link)**
2. Run **olist_sql_script.sql** to clean and prepare the tables.
3. Run **OLIST_KPI_SQL_QUERIES.sql** to generate KPIs and insights.
4. Review query outputs to understand customer behavior, product trends, delivery performance, and seller ranking.


