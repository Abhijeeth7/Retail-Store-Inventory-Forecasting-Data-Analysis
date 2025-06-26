📄 Retail Store Inventory Forecasting – Requirements Document
🧠 Project Name
Retail Store Inventory Forecasting and Sales Analysis

🎯 Objective
To analyze and forecast retail store sales performance from 2022 to 2024 across various dimensions—such as time, geography, product categories, promotions, inventory turnover, and external factors like weather—using Python and its analytical libraries. The goal is to uncover patterns, identify growth opportunities, and enable data-driven decision-making for the business.

📊 Business Requirements (BRs)
BR1	Track year-over-year sales growth from 2022 to 2024.
BR2	Identify best- and worst-selling products across all years.
BR3	Compare pricing of top- and bottom-performing products with competitors.
BR4	Analyze regional sales performance (North, South, East, West) with yearly trends.
BR5	Evaluate sales variation across different weather conditions.
BR6	Determine the impact of product promotions on sales.
BR7	Analyze inventory turnover to flag low-demand products.
BR8	Identify most and least sold product categories.
BR9	Compare performance of stores across regions.
BR10	Study the impact of discounts on demand (deep vs shallow discounts).
BR11	Deliver a comprehensive executive summary with key business insights.
🔍 Granular Analytics Requirements (GARs)
GAR1	Calculate and visualize YoY growth using actual and percentage change metrics.
GAR2	Use total quantity sold to determine product performance rankings.
GAR3	Retrieve price of top/least sold products and benchmark against similar SKUs.
GAR4	Use region-year pivot tables to compare trends and growth rates.
GAR5	Aggregate sales by weather type and assess contribution.
GAR6	Split sales data based on promotion_flag and compare totals and averages.
GAR7	Calculate inventory_left = starting_inventory - quantity_sold, sorted descending.
GAR8	Group by category to rank highest and lowest performers.
GAR9	Aggregate store-level sales and highlight extremes by region.
GAR10	Segment data by discount ranges; evaluate lift in demand/sales across segments.
GAR11	Visual storytelling using graphs to support findings in a final dashboard/report.
