# 📊 Amazon Sales Data Analysis using Excel

## 📌 Overview

This project involves a comprehensive analysis of Amazon Sales dataset using Excel. The goal is to extract actionable insights and answer KPIs related to Product, Product Category, Price, and more.

This README outlines the project’s objectives, KPIs, Excel Approach, and key findings.

---

## 🎯 Objectives

- Data Cleaning for Analyzing and Visualization
- Choosing KPI
- Visualization

---

## 📁 Dataset

- Source: Kaggle - Amazon Sales (https://www.kaggle.com/datasets/ikramshah512/amazon-products-sales-dataset-42k-items-2025)
- Format: CSV
- Cleaned and structured into a Excel

---

## 🧱 Cleaning

```
-Cleaning by Removing Duplicate, Find and Replace, TRIM, PROPER,FILTER.
-Changing Data types by Data Type, Format Cell and Custom.
-Filling missing value by FILL(LEFT,RIGHT, BELOW).
-Creating New Columns by using formulas and Functions Like IF, SEARCH, Aggregate, etc. 

```

---

## 🧠 KPIs

### 1️⃣ Top 10 Best Selling Products

```
-Pivot Table
	Rows: title as Products Name
	Values: bought_lastmonth as Product Sold
-Value Format
	For Product Sold to measure in "K" representing THOUSANDS(KILO).
-Pivot Chart
	Choose Column Chart
```
![KPI1](https://github.com/analyticsaq/AmazonSales_Excel/blob/main/KPI1.png)

---

### 2️⃣ Total Revenue by Categories

```
-Pivot Table
	Rows: product_category as Products Name
	Values: Calcualate Feild -> Total Revenue(bought_lastmonth * discounted_price) as Sum of Total revenue
-Value Format
	For Sum of Total revenue to measure in "M" representing MILLIONS and $ sign.
-Pivot Chart
	Choose Bar Chart
```
![KPI2](https://github.com/analyticsaq/AmazonSales_Excel/blob/main/KPI2.png)

---

### 3️⃣ Monthly Sales

```
-Pivot Table
	Rows: Calculated Items -> delivery_date(August dates as Aug and September dates as Sep) as Month of 2025
	Values: Calcualate Feild -> Total Revenue(bought_lastmonth * discounted_price) as Monthly Revenue
-Value Format
	For Sum of Total revenue to measure in "B" representing BILLIONS and $ Sign.
-Pivot Chart
	Choose Line Chart
```
![KPI3](https://github.com/analyticsaq/AmazonSales_Excel/blob/main/KPI3.png)

---

### 4️⃣ Average Order Values

```
-Pivot Table
	Rows: product_category as Category
	Values: Calcualate Feild -> Average Cost(AVERAGE(discounted_price)) as Item Average Cost
-Value Format
	For Item Average Cost added $ sign.
-Pivot Chart
	Choose Bar Chart
```
![KPI4](https://github.com/analyticsaq/AmazonSales_Excel/blob/main/KPI4.png)

---


## 🎦 Visualization

```
-Removed Gridline
-Fill color
-Add Shapes, Text and Picture
-Copy and Past all four Pivot Chart
-Added Icons, made them Responsive by adding link of sheets to navigate
 Also on others sheets to navigate here and forth.

```
 ![Dashboard](https://github.com/analyticsaq/AmazonSales_Excel/blob/main/Dashboard.png)
---

## 📌 Findings & Conclusions

- **Top 10 Best Selling Products:** Which are most in demand of buyers, useful for sellers.
- **Total Revenue by Categories:** Sellers can choose a strategy according to the these categories revenue. 
- **Monthly Sales:** These report can be useful in strategizing the product launch.
- **Average Order Values:**  Sellers and Buyers both will be helped, by the information of average price of products.

---

## 🚀 Final Thoughts

This Excel-based exploratory data analysis offers a strategic overview of Amazon Sales. These insights can help content strategists, analysts, and business stakeholders make informed decisions around content curation, user targeting, and market focus.
