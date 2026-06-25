# E-Commerce Sales Performance Analysis and Dashboard Development Using Power BI

## Project Overview

This project focuses on analyzing e-commerce sales data using Power BI. The objective is to create meaningful business insights through data modeling, DAX calculations, and interactive visualizations. The dashboard enables users to monitor sales performance, compare actual sales against targets, analyze profitability, and identify regional sales trends.

## Objectives

* Perform data modeling using multiple datasets.
* Create calculated columns using DAX.
* Develop measures for business metrics.
* Implement Year-to-Date (YTD) calculations.
* Build interactive dashboards and visualizations.
* Generate actionable business insights.

## Dataset Used

The project uses three datasets:

### 1. List of Orders

* Order ID
* Order Date
* Customer Name
* City
* State
* Category
* Amount
* Profit

### 2. Order Details

* Order ID
* Category
* Sub-Category
* Quantity
* Amount
* Profit

### 3. Sales Target

* Category
* Month of Order Date
* Target

## Data Modeling

A relationship was created between:

* List of Orders[Order ID]
* Order Details[Order ID]

This relationship allows Power BI to connect order information with sales and profit details.

## DAX Calculations

### Calculated Columns

#### Category Type

Combines Category and Sub-Category into a single field.

#### Revenue per Order

Calculates revenue generated per order.

#### Sales Category

Classifies orders as Above Average or Below Average based on sales amount.

### Measures

#### Order Count

Calculates the total number of unique orders.

#### Average Profit in Delhi

Calculates average profit generated from Delhi orders.

#### Year-to-Date (YTD) Sales

Calculates cumulative sales from the beginning of the year to the selected date.

## Dashboard Visualizations

* Sales Target Achievement by Category (Clustered Column Chart)
* Maximum Profit Margin by Sub-Category (Donut Chart)
* Monthly Sales Trend (Line Chart)
* Profit vs Quantity Analysis (Scatter Chart)
* Total Sales KPI Card
* Total Target KPI Card
* Minimum Target Multi-row Card
* Sales Performance Matrix
* Geographic Sales Analysis Map
* Sales Distribution Treemap
* Order Count Funnel Chart

## Key Insights

* Compare actual sales against assigned targets.
* Identify high-performing product categories.
* Monitor monthly sales trends.
* Analyze profit contribution by sub-category.
* Evaluate regional sales performance.
* Support data-driven business decisions.

## Tools Used

* Power BI Desktop
* DAX (Data Analysis Expressions)
* Data Modeling
* Data Visualization

## Project Outcome

The dashboard provides a comprehensive view of sales performance and business growth. It helps stakeholders monitor targets, track profitability, and identify opportunities for improving sales performance through interactive reporting and visualization.

---

**Author:** DhanaLakshmi
