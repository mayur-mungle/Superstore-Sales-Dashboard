# Superstore-Sales-Dashboard
<img width="1095" height="1216" alt="dashboard" src="https://github.com/user-attachments/assets/c0ff40aa-ef66-4c6c-b7bf-9ee871ea2231" />

# 🛒 Superstore Sales Dashboard

An interactive Excel dashboard built on the Superstore dataset to analyze sales performance, profitability, customer segments, and regional trends.

---

## 📊 Project Overview

This project transforms raw Superstore transactional data into a comprehensive visual dashboard in Excel. It enables business users to monitor KPIs, identify top-performing products and regions, and uncover discount and profit trends — all in one place.

---

## 📁 Dataset Description

The dataset contains order-level transactional records with the following columns:

| Column | Description |
|---|---|
| Order ID | Unique identifier for each order |
| Order Date | Date the order was placed |
| Ship Date | Date the order was shipped |
| Ship Mode | Shipping method used |
| Customer ID | Unique customer identifier |
| Customer Name | Name of the customer |
| Segment | Customer segment (Consumer, Corporate, Home Office) |
| Country | Country of the order |
| City | City of delivery |
| State | State of delivery |
| Postal Code | Postal/ZIP code |
| Region | Geographic region (East, West, Central, South) |
| Product ID | Unique product identifier |
| Category | Product category (Furniture, Office Supplies, Technology) |
| Sub-Category | Product sub-category |
| Product Name | Name of the product |
| Unit Price | Price per unit |
| Quantity | Number of units ordered |
| Original Price | Price before discount |
| Sales | Final sale amount |
| Discount (%) | Discount percentage applied |
| Discounted Value | Amount discounted |
| Profit | Profit earned on the order |
| Profit Margin | Profit as a percentage of sales |

---

## 📈 Dashboard Features

- **Sales Overview** — Total sales, quantity sold, and revenue trends over time
- **Profit Analysis** — Profit and profit margin by category, sub-category, and region
- **Customer Segments** — Breakdown of performance by Consumer, Corporate, and Home Office
- **Regional Performance** — Sales and profit comparison across East, West, Central, and South
- **Top Products** — Best and worst performing products by sales and profit
- **Shipping Analysis** — Orders and delivery patterns by ship mode
- **Geographic Sales Map** — Visual representation of states performance across US states
                             to spot high and low revenue regions instantly
---

## 🛠️ Tools Used

- Microsoft Excel — Dashboard creation, PivotTables, PivotCharts, slicers, and conditional formatting

---

## 🚀 How to Use

1. Download or clone this repository
2. Open the Excel file (Superstore_Dashboard.xlsx)
3. Navigate to the Dashboard sheet
4. Use the slicers to filter by Region, Segment, Category, or Date
5. Explore the charts and KPI cards for insights

---

## 💡 Key Insights

- Technology category drives the highest profit margins
- Furniture shows high sales but lower profitability due to heavy discounting
- The West region leads in total sales, while the South lags in profitability
- Consumer segment accounts for the largest share of orders
- 2017 recorded the highest overall profit compared to all other years

## Limitations

- Pivot tables/KPI sheet is used for intermediate calculations and may not be neatly formatted,
  as it serves as a backend for the dashboard visuals.
