# Sales-Analytics-Dashboard-Excel-Power-BI
A Sales Analytics project — data cleaned in Excel, visualised in a single-page Power BI dashboard — covering 10,684 orders, 175 customers, 30 products, and 3 sales channels from 2014 to 2017.

📌 Project Overview
MetricValueTotal Revenue$205,994,816Total Profit$190,694,432Profit Margin92.6%Total Orders10,684Time PeriodJune 2014 – November 2017


🧹 Phase 1 — Data Cleaning in Excel
TaskDetailRemoved blank columnsBudget sheet had 3 unnamed empty columnsFixed date formatOrderDate serial numbers → DD-MM-YYYYIndex lookupsCustomer/Product/Region indexes mapped using VLOOKUPDerived columnsLine Total = Qty × Unit Price; Profit = Revenue − CostData validationZero nulls, zero duplicates confirmed across 10,684 rows
Functions used: VLOOKUP · INDEX-MATCH · SUMIF · IF · TEXT · IFERROR

📊 Phase 2 — Power BI Dashboard (Single Page)
A clean, single-page overview dashboard with the following visuals:

KPI Cards — Total Revenue, Total Profit, Profit Margin, Total Orders
Revenue by Channel — Wholesale (54%) · Distributor (31%) · Export (15%)
Top 5 Customers — Aibox Company led at $2.1M
Top 5 Products — Product 26 topped at $19.5M
Sales by Country — Germany #1 at $38.8M
Budget vs Actual (2017) — $62.7M budget vs $51.4M actual (−18% variance)


🛠️ Tools Used
Microsoft Excel · Power BI Desktop · Power Query · DAX
