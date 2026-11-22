# Supply-Chain-Analysis-
Power BI supply chain analytics dashboard tracking procurement spend vs target, supplier risk, and delivery delays across 480 purchase orders (₹991.94M spend). Finds that on-time delivery (63.71%) is the key problem, not cost.
Supply Chain Analytics Dashboard
Overview

An interactive Power BI dashboard that tracks procurement spend, supplier performance, and delivery reliability for a supply chain operation (Jan 2025 to Jan 2026). It helps procurement teams see where spend deviates from target and where delivery delays originate.

Business Problem

Procurement spend stayed about ₹18M below target, but only 63.71% of orders arrived on time. The dashboard pinpoints which transport modes, carriers, regions, and categories drive the delays.

Key Metrics
Metric	Value
Actual Spend	₹991.94M
Total Purchase Orders	480
On-Time Delivery	63.71%
Avg Lead Time	10.43 days
Rejection Rate	0.82%
Key Insights
On-time delivery (63.71%) is the main improvement area, even though spend is under target.
Road accounts for the most delayed shipments (302), followed by Rail (113) and Air (72).
Within Rail, RailCargo Connect has the most delays (49), then TCI Express (37) and SwiftHaul Logistics (27).
72.92% of suppliers are rated medium risk and 27.08% low risk.
Office & IT Supplies shows the largest spend variance (₹6.3M), followed by Electrical & Electronics (₹3.9M).
93.57% of POs are closed, 5.26% cancelled, 1.17% open.
Dashboard Features
Actual vs target monthly spend
Spend variance by product category
PO status and supplier risk breakdown
Delivery delay decomposition tree (mode → carrier → region → category)
Filters for month, supplier, and date range, plus quarter buttons
Tools

Power BI, DAX, Excel/SQL (keep only what you used)
