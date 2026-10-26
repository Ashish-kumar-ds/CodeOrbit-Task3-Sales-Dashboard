# CodeOrbit Tech – Task 3: Sales Dashboard

## Objective
Create a dashboard to summarize revenue, order count, units sold, and sales performance by product, category, region, and date.

## Files in this repository
- `sales_dashboard_dataset.csv` — sample dataset for practice.
- `dashboard.html` — interactive browser-based dashboard preview with KPI cards, charts, filters, and order details.
- `dashboard_build_guide.md` — steps for creating the required Power BI dashboard.
- `DAX_measures.txt` — suggested DAX measures for Power BI.

## View the dashboard preview
Open [dashboard.html](./dashboard.html) in GitHub and choose **Raw** or download the file and open it in a web browser. The Date, Region, and Category filters update the KPIs and charts.

## Important dataset note
The CSV in this repository is a sample dataset for demonstration, not an official dataset supplied by CodeOrbit Tech. If the internship provided an official dataset, use that official dataset instead.

## Create the required Power BI file
The HTML preview is not a Power BI `.pbix` file. If CodeOrbit requires a Power BI report, follow these steps in Power BI Desktop:
1. Select **Home → Get data → Text/CSV** and import `sales_dashboard_dataset.csv` (or the official dataset if supplied).
2. Confirm data types: Date = Date, Quantity = Whole number, Unit_Price and Revenue = numeric.
3. In **Modeling → New measure**, add the measures listed in `DAX_measures.txt`.
4. Add KPI cards for Total Revenue, Total Orders, Units Sold, and Average Order Value.
5. Add a bar chart for Revenue by Product or Category, a chart for Revenue by Region, a donut chart for Revenue by Category, and a line chart for Revenue by Date.
6. Add slicers for Date, Region, and Category.
7. Format titles, currency, labels, and layout.
8. Save the finished Power BI file as `Sales_Dashboard.pbix`.
9. Upload `Sales_Dashboard.pbix` to this repository using **Add file → Upload files → Commit changes**.

## Final submission
The `.pbix` file must be created and saved in Power BI Desktop. The interactive `dashboard.html` is included as an extra preview and does not replace a required `.pbix` file.
