# 📊 Global Superstore Analytics Dashboard

## Overview

This project is an end-to-end Business Intelligence solution built in Power BI using the Global Superstore dataset. The dashboard provides actionable insights into sales performance, customer behavior, product profitability, and logistics operations across multiple markets and regions.

The solution was designed using a Star Schema data model and advanced DAX calculations to support executive-level decision-making through interactive reporting and KPI monitoring.

---

## Business Objectives

* Track overall business performance.
* Monitor Year-over-Year (YoY) growth.
* Identify top-performing markets, categories, and products.
* Analyze customer segments and profitability.
* Evaluate logistics and shipping efficiency.
* Detect loss-making products and discount impact.

---

## Dashboard Pages

### 1. Executive Summary

Provides a high-level overview of business performance.

#### KPIs

* Total Sales
* Total Profit
* Profit Margin
* Orders
* Average Order Value (AOV)
* YoY Growth Indicators

#### Key Insights

* Sales increased by **51.54% YoY**.
* Profit increased by **52.25% YoY**.
* APAC generated **28.36%** of total sales.
* Technology is the top-performing category.
* Consumer is the largest customer segment.
* Standard Class accounts for approximately **60%** of shipments.

---

### 2. Sales Analysis

Analyzes revenue and profitability across categories and regions.

#### KPIs

* Technology Sales
* Furniture Sales
* Office Supplies Sales
* Top Performing Region

#### Visuals

* Sales by Category
* Sales vs Profit by Sub-Category
* Top 10 Sub-Categories by Sales

#### Insights

* Technology generated the highest revenue.
* Phones were the best-selling sub-category.
* Central region delivered the strongest sales performance.

---

### 3. Customer Analysis

Provides customer and segment-level insights.

#### KPIs

* Total Customers
* Consumer Sales
* Corporate Sales
* Home Office Sales

#### Visuals

* Sales by Segment and Year
* Profit by Segment
* Customer Performance Table

#### Insights

* Consumer segment contributes the highest sales and profit.
* Customer profitability varies significantly across segments.
* High revenue does not always translate to high profit.

---

### 4. Product Analysis

Evaluates product profitability and discount effectiveness.

#### KPIs

* Unique Products
* Average Discount
* Best Margin Category
* Loss-Making SKUs

#### Visuals

* Discount vs Profit Margin
* Sales by Year and Category
* Product Performance Table

#### Insights

* Higher discounts negatively impact profit margins.
* Technology achieved the highest profit margin.
* Several SKUs operate at a loss and require optimization.

---

### 5. Logistics Analysis

Monitors shipping performance and operational efficiency.

#### KPIs

* Average Shipping Days
* Standard Class Percentage
* Average Shipping Cost
* Critical Order Percentage

#### Visuals

* Orders by Ship Mode
* Average Shipping Cost by Ship Mode & Category
* Orders by Order Priority
* Average Shipping Days by Ship Mode

#### Insights

* Standard Class is the dominant shipping mode.
* Same Day shipping delivers the fastest service.
* Shipping costs vary significantly by category and shipping method.

---

## Data Model

### Fact Table

* FactSales

### Dimension Tables

* DimDate
* DimCustomer
* DimProduct
* DimGeography

### Model Design

* Star Schema

---

## DAX Measures

Examples of key calculations:

```DAX
Total Sales = SUM(FactSales[Sales])

Total Profit = SUM(FactSales[Profit])

Profit Margin =
DIVIDE(
    [Total Profit],
    [Total Sales]
)

Orders =
DISTINCTCOUNT(FactSales[Order_ID])

Avg Shipping Cost =
AVERAGE(FactSales[Shipping_Cost])
```

---

## Tools & Technologies

* Power BI Desktop
* Power Query
* DAX
* Data Modeling
* Data Visualization
* Business Intelligence
* Data Storytelling

---

## Skills Demonstrated

* Data Cleaning & Transformation
* Star Schema Modeling
* DAX Calculations
* KPI Design
* Business Analysis
* Interactive Dashboard Design
* Logistics Analytics
* Customer Analytics
* Sales Analytics
* Product Performance Analysis

---

## Results

✔ Built a complete multi-page business intelligence solution.

✔ Implemented Year-over-Year performance tracking.

✔ Developed executive-level KPI reporting.

✔ Created interactive navigation and filtering experience.

✔ Delivered insights across Sales, Customers, Products, and Logistics.

---

## Author

**Mohamed Ashraf**

Data Analyst | Odoo Implementor Trainee | Business Intelligence Enthusiast

[ Add Your LinkedIn Profile](https://www.linkedin.com/in/mohamedmogin/)

## Summary

![Summary](images/Summary.png)

## Sales Analysis

![Sales](images/Sales.png)

## Product Analysis

![Product](images/Product.png)

## Customer Analysis

![Customer](images/Customer.png)

## Logistics Analysis

![Logistics](images/Logistics.png)
