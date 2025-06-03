# Superstore Data Visualization – Power BI 

This project uses the **Sample - Superstore** dataset to create a compelling data visualization report in **Power BI**, focused on uncovering key business insights through storytelling dashboards.

##  Dataset
- **Source**: [Sample - Superstore.xls]
- Contains: Order, Sales, Profit, Discount, Shipping, Region, Customer, and Product data

##  Tools Used
- **Power BI Desktop**
- DAX for calculated columns and measures

##  Report Pages Overview

1. **Executive Summary** – KPI Cards, Sales Trends, Profit by Region
2. **Category Analysis** – Sales & Profit by Category/Sub-Category
3. **Geographic View** – State-wise Sales & Profit using Map
4. **Customer Segments** – Segment-wise Profit and Discount analysis
5. **Recommendations** – Summary of insights and strategic actions

##  Key Calculations
- `Days to Ship`: Difference between Order Date and Ship Date using:
  ```dax
  Days to Ship = DATEDIFF('Orders'[Order Date], 'Orders'[Ship Date], DAY)
