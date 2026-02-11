# 🚴 Bike Sales Dashboard | Power BI

## 📌 Project Overview

This project presents an **interactive Power BI dashboard** designed to analyze **Bike Sales performance** across multiple dimensions such as time, products, customers, and regions.
The dashboard transforms raw sales data into actionable insights to help stakeholders track performance, identify trends, and support data-driven business decisions.

---

## 🎯 Business Problem & Objective

### Business Problem

Bike retail companies need clear visibility into:

* Overall sales and revenue performance
* Top-performing products and categories
* Regional and customer-level sales behavior
* Profitability trends over time

Without proper dashboards, decision-makers struggle to identify growth opportunities and performance gaps.

### Project Objective

* Build a **centralized Power BI dashboard** to monitor bike sales performance
* Provide clear KPIs for management and business teams
* Enable interactive analysis by region, product, and time

---

## 🛠️ Tools Used

* **Power BI Desktop**
* **Power Query** for data cleaning and transformation
* **DAX** for calculated measures and KPIs
* Data Modeling (Relationships & Star Schema)
* Interactive Visualizations & Slicers

---

## 📂 Data Sources & Key Columns

The project uses multiple related datasets:

### 📊 Sales Table

* Order Date
* Order Quantity
* Sales Amount
* Cost
* Profit

### 🚲 Product Table

* Product Name
* Product Category
* Sub-Category

### 👥 Customer Table

* Customer ID
* Gender
* Age Group

### 🌍 Region Table

* Country
* Region

These tables are connected through a structured data model inside Power BI.

---

## 🔄 Data Analysis Workflow

1. **Data Cleaning & Transformation (Power Query)**

   * Removed duplicates and handled missing values
   * Standardized column names and data types
   * Prepared fact and dimension tables

2. **Data Modeling**

   * Created relationships between Sales, Products, Customers, and Regions
   * Applied a clean star-schema model for better performance

3. **DAX Calculations**

   * Total Sales
   * Total Profit
   * Profit Margin
   * Quantity Sold
   * Time-based measures (YTD / trends)

4. **Visualization & Dashboard Design**

   * Designed interactive report pages
   * Added slicers for dynamic filtering
   * Focused on clarity and business storytelling

---

## 📈 Key KPIs & Insights

### KPIs

* Total Sales Revenue
* Total Profit
* Quantity Sold
* Profit Margin

### Insights

* Identified top-performing bike categories contributing the highest revenue
* Highlighted regional sales differences across countries
* Analyzed customer segments driving the majority of sales
* Tracked sales trends over time to spot growth and decline periods
