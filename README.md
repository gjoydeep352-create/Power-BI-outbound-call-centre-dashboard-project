# Power-BI-outbound-call-centre-dashboard-project
A single-page Power BI dashboard built to unify outbound sales and call centre performance tracking — giving a real-time, decision-ready view of agent productivity, product performance, and conversion efficiency.
Problem Statement

Outbound sales and call centre teams often track calls, orders, and agent performance across disconnected spreadsheets, making it hard to answer simple questions like:

Which agents are converting calls into orders effectively?
Which products are driving the most sales?
How efficient are agents in terms of average handle time (AHT)?

This dashboard consolidates all of that into one interactive view.

📊 Key KPIs
KPI	Value
Total Sales	₹244.41K
Total Calls	1K
Total Orders	192
Average AHT	5.88
Conversion Rate	19.20%
🔍 Features
Agent-level performance view — Sum of Sale and Total Orders by Agent
Product-level breakdown — Sum of Sale and Order distribution by Product
Detailed data table — Agent-wise Sale, Calls Made, Orders, and AHT
Interactive filters — Filter by Agent and Product
Date range slicer — Track performance trends over time
Drill-through support — Cross-report and page-level filtering enabled
🛠️ Tools & Tech
Power BI Desktop
DAX (measures for Total Sales, Total Calls, Total Orders, Average AHT, Conversion Rate)
Power Query (data transformation)
📁 Data Model

Single fact table: Call_Centre_Data with fields including Agent, Product, Date, Sale, Calls Made, Call Duration, Call Outcome, Customer Rating, Revenue (INR), Month, and Top Selling Product.

🚀 How to Use
Clone/download this repo
Open the .pbix file in Power BI Desktop
Refresh data source if connected to a live dataset
Explore via filters, slicers, and drill-through pages
