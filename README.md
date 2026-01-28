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

Ensures full historical coverage (2023–2025)

Fixes missing revenue values
   
Creates a clean profit field used directly in Power BI

Produces a single analytical table for modeling

Power BI Data Model & Measures
KPI Selector Measure (Dynamic Metric Switching)

![image-URL](https://github.com/subsky24/GRIND-SALES/blob/main/IMAGES/Screenshot%20(305).png?raw=true)

Gross Margin Percentage (GMP)

https://github.com/user-attachments/assets/a0f8cc59-e44e-4614-b0bd-36dec2ff96e8


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

![image-URL](https://drive.google.com/file/d/1huIKzEa05RH8I7Y34zMljyiY4A-sm7rY/view?usp=sharing)

🔍 Key Insights (Q3 Focus)

 Multiple products fall below the 30% gross margin threshold
 
 Low-margin products are largely driven by:
 
 Rising input costs

 Fixed pricing structures
 
 Low pricing power in accessories

💡 Pricing & Portfolio Recommendations
❌ Discontinue or Aggressively Reprice (≥ 25%)

The following products are structurally weak and dilute overall profitability:

Chemex Filters
Lowest total gross margin (16.31%)

Minimalist Keychain

Logo Hoodie

Action: Immediate review. Either discontinue or apply a steep price increase to justify continued production.

⚠️ Price Adjustment Required

Gooseneck Electric Kettle

Action: Moderate price increase to restore gross margin above the 30% minimum threshold.

📌 Business Justification

These actions are necessary because:

Rising COGS has made certain SKUs economically inefficient

Low-margin items consume operational capacity without proportional returns

Strategic pruning improves overall portfolio health and pricing power
