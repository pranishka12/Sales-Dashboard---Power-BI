# 📊 Sales Dashboard – Power BI Project

## Project Overview

This Sales Dashboard was developed using Power BI to provide meaningful insights into business sales performance. The dashboard enables users to monitor key metrics, analyze trends, identify top-performing products and regions, and support data-driven decision-making.

---

## Objectives

* Analyze overall sales performance.
* Track revenue and profit trends.
* Identify top-performing products and regions.
* Monitor customer purchasing patterns.
* Support strategic business decisions through interactive visualizations.

---

## Tools & Technologies

* Power BI
* Power Query
* DAX (Data Analysis Expressions)
* Microsoft Excel / CSV

---

## Dataset Information

The dataset contains transactional sales data including:

* Order Details
* Product Information
* Customer Information
* Sales and Profit Metrics
* Regional Performance Data
* Order Dates

---

## Data Preparation

The following data transformation steps were performed:

* Removed duplicate records
* Handled missing values
* Corrected data types
* Created calculated columns
* Built relationships between tables
* Optimized the data model for reporting

---

## Dashboard Features

### Executive KPIs

* Total Sales
* Total Profit
* Total Orders
* Average Order Value
* Profit Margin

### Sales Analysis

* Monthly Sales Trend
* Yearly Performance Comparison
* Revenue Growth Analysis

### Product Analysis

* Top Selling Products
* Category-wise Sales Performance
* Profit Contribution by Product

### Regional Analysis

* Sales by Region
* Profit by Region
* Regional Performance Comparison

### Interactive Functionality

* Date Filters
* Region Filters
* Product Filters
* Dynamic Visual Interactions

---

## DAX Measures Used

```DAX
Total Sales = SUM(Sales[Sales])

Total Profit = SUM(Sales[Profit])

Total Orders = DISTINCTCOUNT(Sales[Order ID])

Profit Margin = DIVIDE([Total Profit],[Total Sales],0)

Average Order Value =
DIVIDE([Total Sales],[Total Orders],0)
```

---

## Business Questions Answered

* Which region generates the highest revenue?
* Which products contribute the most profit?
* What are the monthly sales trends?
* How does profit vary across regions?
* Which categories drive business growth?

---

## Key Insights

* Identified top-performing regions and products.
* Revealed seasonal sales trends.
* Highlighted profitable customer segments.
* Enabled better inventory and sales planning.
* Supported business decision-making through visual analytics.

---

## Skills Demonstrated

* Data Cleaning
* Data Transformation
* Data Modeling
* DAX Calculations
* Business Intelligence
* Dashboard Development
* Data Visualization
* Analytical Thinking

---

## Future Enhancements

* Sales Forecasting
* Customer Segmentation
* Drill-through Analysis
* Automated Data Refresh
* AI-Powered Insights

---

## Dashboard Preview

*(Add dashboard screenshots here)*

---

## Author

**Pranishka Sivakumar**

Aspiring Data Analyst

Skills: Power BI | Excel | SQL | Python | Data Visualization
