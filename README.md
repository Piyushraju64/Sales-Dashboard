# 🍕 Pizza Sales Analysis | SQL & Power BI

An end-to-end **Pizza Sales Analysis project** using **SQL and Microsoft Power BI** to analyze sales performance, revenue trends, customer ordering patterns, and product performance.

## 🎯 Project Objective

The objective of this project is to transform raw pizza sales data into meaningful business insights using **SQL queries, DAX calculations, and interactive Power BI visualizations**.

## 🛠️ Tools Used

- **SQL** – Data analysis and business queries
- **Power BI** – Interactive dashboard and visualization
- **DAX** – KPI calculations and measures
- **Power Query** – Data cleaning and transformation
- **CSV** – Source dataset

## 🗄️ SQL Analysis

SQL was used to answer business questions related to:

- Total Revenue
- Total Orders
- Total Pizzas Sold
- Average Order Value
- Pizza Category Performance
- Pizza Size Performance
- Daily and Monthly Sales
- Hourly Order Trends
- Top-Performing Pizzas

The completed SQL queries and solutions are included in **`PIZZA SALES SQL QUERIES.docx`**.

## 📊 Power BI Dashboard

The interactive dashboard provides:

- 💰 **Total Revenue:** $817.86K
- 🧾 **Total Orders:** 21K
- 🍕 **Total Pizzas Sold:** 50K
- 💵 **Average Order Value:** $38.31
- 🛒 **Average Pizzas Per Order:** 2.32

### Dashboard Visuals

- Revenue Trend
- Orders by Day of Week
- Total Orders by Hour
- Revenue by Category
- Top 10 Pizzas
- Customer Spending Analysis

### Interactive Filters

- Category
- Size
- Month

## 🔍 Key Insights

- Total revenue generated is approximately **$817.86K**.
- Approximately **21K orders** and **50K pizzas** were recorded.
- The average order value is approximately **$38.31**.
- Customers purchase an average of **2.32 pizzas per order**.
- Order activity varies across different days of the week.
- Ordering activity shows noticeable peaks during lunchtime and evening hours.
- Revenue is relatively balanced across the major pizza categories.
- The Top 10 analysis highlights the strongest-performing pizza products.

## 🧮 DAX

DAX measures were created for dynamic KPI calculations, including:

```DAX
Total Orders = DISTINCTCOUNT(pizza_sales[order_id])
Average Order Value =DIVIDE([Total Revenue], [Total Orders])
Average Pizzas Per Order =DIVIDE([Total Pizzas Sold], [Total Orders])

Project Workflow

Dataset → SQL Analysis → Data Transformation → DAX → Power BI Dashboard → Business Insights

Project Files
Sales Dashboard.pbix – Power BI dashboard
pizza_sales.csv – Dataset
PIZZA SALES SQL QUERIES.docx – SQL queries and solutions
Dashboard final.PNG – Dashboard preview
README.md – Project documentation

Skills Demonstrated

SQL | Power BI | DAX | Power Query | Data Analysis | Data Visualization | Business Intelligence | Dashboard Design
Total Revenue = SUM(pizza_sales[total_price])
