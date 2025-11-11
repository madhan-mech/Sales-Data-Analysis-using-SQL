# Sales-Data-Analysis-using-SQL
To analyze company sales performance, profit trends, and customer insights using SQL queries
## 📘 Project Overview
This project analyzes retail sales data using SQL to uncover key business metrics and performance trends.  
The goal is to identify top-performing regions, products, and customer segments, and provide data-driven insights for improving sales and profitability.

-------

## 🗂️ Dataset Information
Two datasets were used:

- **orders** — Contains customer and order-level details (Order ID, Customer Name, City, State, etc.)
- **details** — Contains sales transaction details (Order ID, Product, Quantity, Profit, and Amount)

---

## 🛠️ Tools & Technologies
- **SQL** (MySQL / SQLite)
- **Joins**, **Group By**, **Aggregations**, **Order By**, **Limit**
- **Functions used:** `SUM()`, `COUNT()`, `AVG()`, `DISTINCT()`, `CASE WHEN`

---

## 📊 Key KPIs (Metrics)

| # | KPI | Description |
|---|-----|--------------|
| 1 | **Total Sales** | Total revenue generated from all transactions |
| 2 | **Total Profit** | Sum of profits across all sales |
| 3 | **Total Orders** | Total number of unique orders placed |
| 4 | **Total Customers** | Total number of distinct customers |
| 5 | **Total Quantity Sold** | Sum of product quantities sold |
| 6 | **Top Category Sales** | Product category with highest total sales |
| 7 | **Top 5 Cities by Sales** | Cities contributing most to total sales |
| 8 | **Top 5 States by Sales** | Top-performing states by revenue |
| 9 | **Top 5 Sub-Categories** | Sub-categories driving most profit or sales |
| 10 | **Mode of Payment Analysis** | Distribution of orders by payment type |

---

| # | Insight                     | Explanation                                                                                                                   |
| - | --------------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| 1 | **Top Performing States**   | Maharashtra and Delhi lead in total sales, showing strong demand and customer base in metropolitan regions.                   |
| 2 | **High-Revenue Categories** | The *Technology* and *Office Supplies* categories generate the highest revenue, indicating strong B2B and electronics demand. |
| 3 | **Profit Variability**      | Furniture category shows good sales but relatively lower profit margins — possible high cost or discounts.                    |
| 4 | **Customer Distribution**   | Majority of sales come from repeat customers in major cities — shows brand trust but dependency on limited regions.           |
| 5 | **Payment Preferences**     | Most customers prefer digital payments, showing a shift toward online and cashless transactions.                              |
| 6 | **Order Trends**            | Orders are higher in Q4 months, suggesting seasonal spikes (festive or financial-year end sales).                             |
| 7 | **Sub-Category Leaders**    | Accessories, Phones, and Chairs drive consistent sales volume, highlighting product stability across markets.                 |

------

| # | Area                    | Recommendation                                                                                            | Expected Benefit                                   |
| - | ----------------------- | --------------------------------------------------------------------------------------------------------- | -------------------------------------------------- |
| 1 | **Regional Expansion**  | Focus marketing campaigns on mid-tier states (e.g., Gujarat, Tamil Nadu) to balance regional performance. | Increases overall sales coverage and market reach. |
| 2 | **Profit Optimization** | Re-evaluate pricing and vendor strategy in low-margin categories like Furniture.                          | Improves profit margin without reducing volume.    |
| 3 | **Customer Retention**  | Introduce loyalty programs and personalized offers for high-value customers.                              | Boosts repeat purchases and lifetime value.        |
| 4 | **Product Portfolio**   | Promote high-profit sub-categories (e.g., Accessories, Phones) via targeted ads.                          | Maximizes ROI on marketing spend.                  |
| 5 | **Inventory Planning**  | Use sales data by city/sub-category to forecast demand and optimize stock levels.                         | Reduces overstocking and stock-outs.               |
| 6 | **Payment Strategy**    | Encourage less-used payment modes (like UPI or cards) through small discounts.                            | Increases conversion rate and convenience.         |
| 7 | **Seasonal Campaigns**  | Prepare marketing and logistics ahead of Q4 demand spikes.                                                | Captures peak-season sales efficiently.            |


