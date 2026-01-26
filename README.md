# GRIND-SALES
## Coffee Sales Portfolio Optimization (2023–2025)

📌 Project Overview

This project analyzes coffee business sales performance across 2023–2025 to address a critical business challenge: declining profit margins caused by rising costs of goods, tariffs, and operational pressures.

Using SQL for data integration and transformation and Power BI for analytics and visualization, the project evaluates product-level profitability and provides clear, data-backed pricing recommendations to restore sustainable margins.

The primary business rule guiding the analysis is a minimum acceptable Gross Margin Percentage (GMP) of 30%.
🎯 Business Problem

The company has observed a significant decline in gross profit margins across its product portfolio. Preliminary investigations suggest that increasing COGS and external cost pressures are eroding profitability.

Key Business Question

Which products are underperforming on margin, and should they be repriced or discontinued to protect overall profitability?

🗂️ Datasets Used

The analysis integrates multiple datasets:

1. Orders Data (2023–2025): OrderID, CustomerID, ProductID,OrderDate, Quantity, Revenue,COGS

2. Customers Data :CustomerID,Region,CustomerJoinDate

3. Products Data

ProductID,ProductName,ProductCategory,Price,Base_Cost

🛠️ Tools & Technologies

SQL – Data consolidation, cleaning, profit calculations

Power BI – Data modeling, DAX measures, dashboards, insights

Power Query – Minor transformations and data validation

  🔄 Data Integration Logic (SQL)
 Consolidating Orders Across Years

![image-URL](https://github.com/subsky24/GRIND-SALES/blob/main/IMAGES/Screenshot%20(306).png?raw=true)

Why This Matters
  . Ensures full historical coverage (2023–2025)
  . Fixes missing revenue values
  . Creates a clean profit field used directly in Power BI
  . Produces a single analytical table for modeling

Power BI Data Model & Measures
KPI Selector Measure (Dynamic Metric Switching)

![image-URL](https://github.com/subsky24/GRIND-SALES/blob/main/IMAGES/Screenshot%20(305).png?raw=true)

Gross Margin Percentage (GMP)

![image-URL](https://github.com/subsky24/GRIND-SALES/blob/main/IMAGES/Screenshot%20(307).png?raw=true)



📈 Dashboard Features
     The Power BI dashboard provides:
     . Year-over-Year Gross Margin % Trend
     . Revenue Breakdown by:
     . Product Category
     . Product
     . Region
     . Q3 Margin Filter to isolate underperforming products
     . Dynamic KPI Cards (Revenue, Profit, Quantity, Margin)

This enables executives to quickly spot margin leakage and take action.

![image-URL](https://github.com/subsky24/GRIND-SALES/blob/main/IMAGES/Screenshot%20(304).png?raw=true)

![image-URL](https://github.com/subsky24/GRIND-SALES/blob/main/IMAGES/Screenshot%20(304).png?raw=true)
