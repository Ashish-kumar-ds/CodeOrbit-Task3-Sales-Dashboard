# Dashboard Build Guide

## Suggested layout
- Top row: KPI cards — Total Revenue, Total Orders, Units Sold, Average Order Value.
- Left: Revenue by Product (bar chart).
- Right: Revenue by Region (column chart).
- Bottom-left: Revenue by Category (donut chart).
- Bottom-right: Revenue over Time (line chart).
- Add slicers for Date, Region, and Category.

## Import and prepare data
1. In Power BI Desktop, choose **Get data → Text/CSV**.
2. Select `sales_dashboard_dataset.csv`.
3. Confirm Date is a Date column, Quantity is Whole Number, and Unit_Price / Revenue are numeric.
4. Select **Close & Apply**.

## Create visuals
- Card: Total Revenue.
- Card: Total Orders.
- Card: Units Sold.
- Card: Average Order Value.
- Bar chart: Axis = Product; Values = Total Revenue.
- Column chart: Axis = Region; Values = Total Revenue.
- Donut chart: Legend = Category; Values = Total Revenue.
- Line chart: X-axis = Date; Y-axis = Total Revenue.
- Slicers: Date, Region, Category.

## Save
Choose **File → Save As** and save as `Sales_Dashboard.pbix`. Check internship instructions to confirm whether the PBIX file, screenshots, or a published dashboard link are required.
