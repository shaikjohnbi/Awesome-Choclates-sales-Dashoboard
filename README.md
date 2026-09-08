Awesome Chocolates Sales Dashboard — Interactive Power BI sales analysis dashboard & Excel dataset evaluating over 25,000 global shipment transactions (2023–2025). Features multi-dimensional data modeling across 22 products, 6 countries, 4 sales teams, and order fulfillment metrics.

# 🍫 Awesome Chocolates Sales Dashboard & Analytics

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

## 📌 Project Overview
This repository contains an end-to-end **Business Intelligence & Sales Performance Dashboard** for **Awesome Chocolates**, built using **Power BI** (`powerbi-demo-1.pbix`) and structured **Excel data** (`chocolates sales 2025.xlsx`).

The dataset contains **25,076 transactional shipment records** spanning from **2023 to 2025**, tracking sales revenue, profit margins, box quantities, order statuses, and performance across products, geographies, and sales teams.

---

## 📊 Dataset & Data Model

The analysis is based on a relational star schema structure:

### 1. Fact Table (`Shipments`) — 25,076 Records
- `ShipmentID`: Unique identifier for each shipment transaction.
- `SPID`: Salesperson ID (mapped to Sales Reps).
- `PID`: Product ID (mapped to Product Catalogue).
- `GID`: Geography ID (mapped to Countries & Regions).
- `Shipdate`: Shipment date (2023–2025).
- `Amount`: Total Revenue / Sales value ($).
- `Boxes`: Quantity of chocolate boxes shipped.
- `Order_Status`: Order state (`Delivered`, `Cancelled`, `Placed`, `Shipped`).

### 2. Dimension Tables (`Dimension Data`)
- **Products (22 Items):** Categorized into *Bars*, *Bites*, and *Other* with explicit `Cost_per_box` (e.g., Milk Bars, 50% Dark Bites, Almond Choco, 85% Dark Bars, Organic Choco Syrup).
- **Geography (6 Countries, 3 Regions):**
  - **APAC:** India, New Zealand, Australia
  - **Americas:** USA, Canada
  - **Europe:** UK
- **Sales Teams (25 Reps, 4 Teams):** Sales reps grouped into *Yummies*, *Delish*, *Jucies*, and *Tempo*.

### 3. Calendar Table (`Calendar`)
- Date dimension mapping days, weekday names, weekday numbers, months, quarters, and calendar years (822 dates).

---

## 🎯 Key Business Metrics & Visual Insights

- **Financial KPIs:** Total Sales Revenue ($), Total Cost ($), Gross Profit ($), Overall Profit Margin (%), and Total Boxes Sold.
- **Product Category Breakdown:** Profitability comparison between high-volume product categories (*Bars* vs. *Bites* vs. *Specialty items*).
- **Regional Sales Distribution:** Market share comparison across APAC, Americas, and Europe.
- **Sales Rep Leaderboard:** Identification of top-performing sales representatives and team-level productivity comparisons.
- **Fulfillment & Logistics Health:** Order status analytics identifying cancellation rates and delivery throughput.

---

## 📂 Repository File Structure


---

## 💻 How to View & Run the Dashboard

1. **Prerequisites:** Install [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/) (Free).
2. **Clone the Repository:**
   ```bash
