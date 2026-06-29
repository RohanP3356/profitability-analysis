# Profitability-Analysis
An interactive Sales Performance and Profitability dashboard built using Power BI and Microsoft Excel. Features dynamic data modeling with Excel Pivot Tables and Power BI cross-filtering to track core business KPIs, analyze product profitability, and uncover regional sales insights.
📊 Sales Performance & Profitability Report

Overview

This repository contains a comprehensive Sales Performance & Profitability Analysis for a US-based retail business. The project includes raw transactional sales data and an interactive Power BI dashboard that enables data-driven decision-making across regions, product categories, and customer segments.


📁 Repository Contents

FileDescriptionSales_Performance___Profitability_Report.xlsxRaw sales dataset with order-level transaction recordsSales_Performance___Profitability_Report.pbixInteractive Power BI dashboard for visual analysis


📋 Dataset Description

File: Sales_Performance___Profitability_Report.xlsx

Sheet: Sales Data

The dataset contains granular order-level records of US retail sales transactions. Each row represents a single order with the following fields:

ColumnDescriptionOrder_IDUnique identifier for each orderOrder_DateDate the order was placedCustomer_NameFull name of the customerCityCity of the customerStateUS state of the customerRegionSales region (East, West, South, Centre)CountryCountry (United States)CategoryTop-level product category (Electronics, Clothing & Apparel, Home & Furniture, Accessories)Sub_CategoryProduct sub-category (e.g., Smartphones, Sportswear, Bedding)Cleaned_ProductCleaned/standardized product nameQuantityNumber of units orderedUnit_PricePrice per unit (USD)RevenueTotal revenue for the order (Quantity × Unit_Price)ProfitProfit generated from the order (USD)

Key Stats at a Glance

Geography: Transactions across all major US regions — East, West, South, and Centre
Categories covered: Electronics, Clothing & Apparel, Home & Furniture, Accessories
Sub-categories: 15+ including Smartphones, Laptops, Wearables, Sportswear, Footwear, Bedding, Kitchenware, and more
Products: 40+ distinct products (e.g., MacBook Air, Apple iPhone 14, Nike Air Force 1, Levi's Jeans, KitchenAid Mixer, Tempur-Pedic Mattress)



📊 Power BI Dashboard

File: Sales_Performance___Profitability_Report.pbix

The Power BI report provides interactive visualizations to explore:

Revenue & Profit Trends — Track performance over time
Regional Analysis — Compare sales across East, West, South, and Centre regions
Category & Sub-Category Breakdown — Identify top-performing product lines
Top Products — Rank products by revenue and profitability
Customer Insights — Understand order volumes and customer distribution by city/state
Profit Margin Analysis — Spot high-revenue but low-margin areas for optimization

Requirements

Microsoft Power BI Desktop (free) to open the .pbix file
No external database connection required — data is embedded in the file


🚀 Getting Started

Clone or download this repository
Open Sales_Performance___Profitability_Report.xlsx in Excel or any spreadsheet tool for raw data exploration
Open Sales_Performance___Profitability_Report.pbix in Power BI Desktop to interact with the dashboard
Use slicers and filters in the dashboard to drill down by region, category, or time period


💡 Use Cases

Sales performance monitoring and KPI tracking
Regional and category-level profitability analysis
Business intelligence reporting and presentations
Data analysis practice with real-world retail data
Learning Power BI with a realistic dataset


🛠️ Tools Used


Microsoft Excel — Data storage and preprocessing
Microsoft Power BI — Interactive dashboard and visualization
Python / Pandas (optional) — For further data analysis or automation

📌 Notes

All data is based in the United States
Order dates are stored as Excel serial numbers; convert using standard date parsing if working programmatically
The Phone Case column in the raw data appears to be a legacy/intermediate field; use Cleaned_Product for accurate product names

📄 License

This project is intended for educational and portfolio purposes. Please credit the repository if you use or adapt this work.

📬 Contact
Name :- Rohan Phulwadkar Email no. :- rohanphulwadkar@gmail.com
