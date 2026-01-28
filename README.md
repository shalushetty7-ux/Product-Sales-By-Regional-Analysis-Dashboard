# Product Sales by Regional Analysis Dashboard
Excel-based Product Sales &amp; Regional Performance Dashboard using Pivot Tables, Pivot Charts, and slicers to analyze sales, profit, and order trends across regions.

## Project Overview
This project focuses on analyzing product sales by region using a comprehensive sales dataset from January 2023 to mid-2025. The goal was to visualize sales performance across regions, store locations, products, and time periods, and to track profitability using Advanced Excel features.

## Dataset Description
[Dataset](https://github.com/shalushetty7-ux/Product-Sales-By-Regional-Analysis-Dashboard/blob/main/Product%20Sales%20By%20Region%20Data%20Analysis%20Dashboard.xlsx)

The dataset contains the following columns:

- **Date, OrderID, OrderDate, DeliveryDate** – Order placement and delivery timelines  
- **Year** – Year extracted for time-based analysis  
- **Region, RegionManager** – Geographic sales region and responsible manager  
- **StoreLocation** – Store where the sale occurred (Store A, Store B, Store C, Store D)  
- **Product** – Product category (Chair, Desk, Phone, Laptop, etc.)  
- **Quantity** – Number of units sold per order  
- **UnitPrice** – Price per unit of the product  
- **TotalPrice (Sales)** – Total sales value for each transaction  
- **Profit** – Profit earned from each order  
- **CustomerName, CustomerType** – Customer details and segment (Retail / Wholesale)  
- **Salesperson** – Sales representative associated with the order  
- **PaymentMethod** – Mode of payment (Cash, Credit Card, Debit Card, Gift Card, Online)  
- **Discount** – Discount applied on the order  
- **Promotion** – Promotional offer used (if any)  
- **Returned** – Indicates whether the product was returned  
- **ShippingCost** – Cost incurred for shipping the order

## Analysis and Dashboard
The analysis was performed entirely in Advanced Excel, including the creation of the following interactive visualizations:

- **Sales in Region vs Count of Orders** – Identifies high-performing regions
- **Sales by Store Location** – Compares sales across different stores
- **Monthwise Sales Chart** – Tracks sales trends by month
- **Sales vs Profit Chart** – Visualizes profit alongside sales

## KPI Card Created
- Total Sales
- Profit Amount
- Total Orders
- Total Profit in % – 30% overall

 Icons were added to each KPI for better visual representation.

 ## Filters / Slicers Used
To make the dashboard interactive and user-friendly, the following filters (slicers) were implemented:

- **Region** – Central, East, North, South, West  
- **Product** – Chair, Desk, Laptop, Monitor, Phone, Tablet  
- **Year** – 2023, 2024, 2025  
- **Month** – January to December  
- **Store Location** – Store A, Store B, Store C, Store D  
- **Customer Type** – Retail, Wholesale  
- **Payment Method** – Cash, Credit Card, Debit Card, Gift Card, Online  
- **Promotion** – FREESHIP, SAVE10, WINTER15, NA
- **Discount** - 0, 0.1, 0.15, 0.05

 All slicers were connected to all Pivot Tables to ensure synchronized filtering.

## Process
- Collected and reviewed the product sales dataset in Excel.
- Performed data cleaning by checking blank values, correcting date formats, and removing duplicates.
- Created new calculated columns such as Year and Profit for analysis.
- Built Pivot Tables to analyze sales, profit, orders, and regional performance.
- Designed Pivot Charts for visual analysis (
  [Month wise Sales](https://github.com/shalushetty7-ux/Product-Sales-By-Regional-Analysis-Dashboard/blob/main/Dashboard/Month%20wise%20sales.jpg), 
   [Sales Vs Profit](https://github.com/shalushetty7-ux/Product-Sales-By-Regional-Analysis-Dashboard/blob/main/Dashboard/Sales%20Vs%20Profit.jpg), 
   [Sales by store location](https://github.com/shalushetty7-ux/Product-Sales-By-Regional-Analysis-Dashboard/blob/main/Dashboard/Sales%20by%20store%20location.jpg),
   [Sales in region Vs Count of orders](https://github.com/shalushetty7-ux/Product-Sales-By-Regional-Analysis-Dashboard/blob/main/Dashboard/Sales%20in%20region%20Vs%20Count%20of%20orders.jpg))
- Added slicers to enable interactive filtering by region, product, year, month, store, customer type, and promotion.
- Created key KPIs such as Total Sales, Profit Amount, Profit in Percentage, and Total Orders.
- Designed a consolidated Excel dashboard with consistent formatting and layout.
- Analyzed trends and insights: Identified top regions, high-sales months, and profit margin.

## Key Insights
**Top Performing Region:** North
**High Sales Months:**
- 2023: March
- 2024: January & October
- 2025: March (dataset up to June 2025)
**Profit Margin:** ~30%

## Dashboard Overview
[Dashboard](https://github.com/shalushetty7-ux/Product-Sales-By-Regional-Analysis-Dashboard/blob/main/Dashboard/Dashboard.jpg)

## Conclusion
This dashboard provides a complete overview of product sales, regional performance, profitability, and order trends.
It helps stakeholders make data-driven decisions by analyzing sales trends, store performance, and profit margins using Excel.


