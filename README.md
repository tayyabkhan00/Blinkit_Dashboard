# Blinkit Power BI Dashboard 📊

## Overview

This project is an **end-to-end Power BI dashboard** built to analyze and visualize the business performance of **Blinkit (India’s Last Minute App)**. The dashboard provides a **360° analytical view** covering **Sales, Customers, Inventory, Feedback, and Marketing** performance using multiple interactive reports.

The goal of this project is to demonstrate **real-world business analytics**, strong **data modeling**, and **Power BI visualization skills**, making it suitable for **Data Analyst / Business Analyst portfolios**.

---

## Live Dashboard

The dashboard was built using **Power BI Desktop** and then **published to Power BI Service** for sharing and interaction.

> ⚠️ Note: Screenshots are provided in this repository. Access to the live published report depends on workspace permissions.

---

## Project Structure

```
Blinkit_Dashboard/
│
├── Data/
│   ├── blinkit_orders.csv
│   ├── blinkit_order_items.csv
│   ├── blinkit_products.csv
│   ├── blinkit_customers.csv
│   ├── blinkit_inventory.csv
│   ├── blinkit_inventoryNew.csv
│   ├── blinkit_delivery_performance.csv
│   ├── blinkit_marketing_performance.csv
│   ├── blinkit_customer_feedback.csv
│   ├── Category_Icons.xlsx
│   ├── Rating_Icon.xlsx
│   └── test_db.sql
│
├── dashboard/
│   └── Blinkit_Dashboard.pbix
│
├── icons/
│   └── UI & category icons
│
├── overview/
│   └── Dashboard screenshots
│
└── README.md
```

---

## Tools & Technologies

* **Power BI Desktop** – Data modeling & dashboard creation
* **Power BI Service** – Dashboard publishing
* **Excel** – Icons & reference tables
* **CSV Datasets** – Transactional and analytical data
* **SQL (test_db.sql)** – Data validation & testing

---

## Data Model

The dashboard uses a **star schema** approach with:

* **Fact Tables**

  * Orders
  * Order Items
  * Inventory
  * Marketing Performance
  * Customer Feedback

* **Dimension Tables**

  * Customers
  * Products
  * Categories
  * Date

Relationships are optimized for **performance and slicer interaction**.

---

## Dashboard Pages & Analysis

### 1️⃣ Sales Overview

**Key Metrics (Last 6 Months):**

* Quantity Sold (2024 vs 2025)
* Sales Growth %
* Daily & Monthly Sales Trends

**Visuals Used:**

* KPI Cards
* Bar + Line Combo Charts
* Top Products by Quantity
* Top Areas by Sales

📌 **Insight:**

* Enables quick comparison between years and identifies sales growth or decline patterns.

---

### 2️⃣ Customer Analysis

**Metrics Covered:**

* Total Customers
* New vs Lost Customers
* Repeat Customers
* Customer Growth by Month

**Advanced Features:**

* Top 5 / 10 / 20 / 50 / 100 customers slicer
* Dynamic customer ranking

📌 **Insight:**

* Helps understand customer retention, loyalty, and churn behavior.

---

### 3️⃣ Feedback & Ratings Analysis

**Key Insights:**

* Feedback sentiment (Positive / Neutral / Negative)
* Feedback category (App Experience, Delivery, Product Quality, Customer Service)
* Rating distribution (1⭐ to 5⭐)

**Visuals Used:**

* Donut Charts
* Detailed Feedback Table
* Emoji-based rating indicators

📌 **Insight:**

* Identifies customer pain points and areas of improvement.

---

### 4️⃣ Inventory Analysis

**Inventory KPIs:**

* Total Stock Received
* Available Stock
* Damaged Stock
* Stock Movement %

**Visuals Used:**

* Line Charts (Stock Movement)
* Gauge Charts (Available vs Damaged Stock)

📌 **Insight:**

* Helps reduce wastage and optimize supply chain efficiency.

---

### 5️⃣ Marketing Performance

**Marketing KPIs:**

* Clicks
* Conversions
* Impressions
* Revenue Generated
* Spend
* ROAS

**Visuals Used:**

* KPI Cards
* Multi-line Trend Charts
* Metric Selector Slicers

📌 **Insight:**

* Evaluates campaign efficiency and return on ad spend.

---

## Key Power BI Features Used

* DAX Measures (Growth %, KPIs, Rankings)
* Dynamic Slicers & Filters
* Custom Icons & UI Design
* Drill-through & Page Navigation
* Tooltips for better storytelling

---

## Business Use


Click below to explore the live dashboard 
👉 [**View Power BI Dashboard**](https://app.powerbi.com/view?r=eyJrIjoiMDY2OTYyMGItYzcyOS00MDdlLTgxOTMtODE0OWE5ZjE3Nzc4IiwidCI6Ijg1YmRkNjUwLWM5NmMtNGQzNy1hZDE3LTRlZWQ4MzJiM2Y0OSJ9)
