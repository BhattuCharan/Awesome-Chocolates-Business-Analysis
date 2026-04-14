📊 Awesome Chocolates — Sales & Profit Analysis Dashboard (Power BI)

This project presents an interactive Power BI dashboard built to analyze sales performance, profitability trends, product-level efficiency, and shipment status distribution for the Awesome Chocolates dataset. The dashboard focuses on profit-driven KPIs to support business-oriented decision-making.

🎯 Project Objectives
Compare Year-over-Year Profit (2024 vs 2023)
Identify high-performing and low-performing products
Analyze country-wise revenue contribution
Evaluate shipment fulfillment performance
Build a product performance matrix using sales, profit, and boxes sold
📈 Key KPIs Implemented
YoY Profit Growth (2024 vs 2023)
Sales by Country
Profit Margin by Product
Product Performance Matrix
Comparison of Total Sales
Comparison of Total Profit
Comparison of Boxes Sold
Order Status Distribution
🧠 Business Insights Delivered
Identified top revenue-contributing countries
Highlighted products generating the highest profit margins
Compared product performance using sales, profit, and shipment volume
Evaluated shipment completion trends across order statuses
Analyzed monthly performance differences between 2023 and 2024
🗂 Dataset Preparation & Modeling

The shipment dataset did not contain total cost directly.

To calculate profit:

Merged Cost per Box from the product table using Product ID, then created:

Total Cost = Cost per Box × Boxes

Profit was derived as:

Profit = Sales − Cost

This enabled margin-based KPI analysis.

📊 Dashboard Features
Executive KPI summary panel
Monthly YoY comparison of sales and profit
Country-level revenue contribution visualization
Product-level profitability comparison table
Conditional formatting for performance highlighting
Shipment status distribution analysis
Interactive date range filtering
