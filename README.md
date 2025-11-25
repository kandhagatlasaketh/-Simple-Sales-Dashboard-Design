SALES DASHBOARD PROJECT – TASK 8
1. Project Overview
This document explains how a sales dashboard was created in Power BI using a Superstore-style dataset. The dashboard visualizes sales performance by month, region, and category to support data-driven analysis.

2. Dataset Summary
Dataset: Superstore Sales (50 Records)
Fields Included:
Order Date
Region
Category
Product
Sales
Profit
The dataset spans January–September 2024.

3. Tools Used
Power BI Desktop (for dashboard creation)
Dataset in CSV/PDF format

4. Dashboard Creation Steps
Step 1 — Import the Dataset
Home → Get Data → CSV/Excel → Load
Step 2 — Prepare Data
Confirm data types
Ensure Order Date is Date type
Close & Apply
Step 3 — Create Month-Year Column
MonthYear = FORMAT('Table'[Order Date], "MMM YYYY")
Step 4 — Create Visuals

Line Chart: Monthly Sales Trend
X-axis → MonthYear
Y-axis → Sales

Bar Chart: Sales by Region
Axis → Region
Values → Sales

Donut Chart: Sales by Category
Legend → Category
Values → Sales

Step 5 — Add Filters
Add slicers for Region and Category

Step 6 — Format the Dashboard
Apply theme
Edit titles
Align visuals cleanly

5. Final Dashboard Layout
The final report page includes:
Line Chart: Monthly Sales Trend
Bar Chart: Sales by Region
Donut Chart: Sales by Category
Slicers: Region, Category
KPI Cards for Total Sales, Profit

6. Insights
West region achieved the highest sales, leading all regions.
Technology is the best-performing category, contributing the largest revenue share.
Sales grew steadily from January to September.
Furniture category shows mixed profitability, with some negative-profit items.

7. Conclusion
The Power BI dashboard provides a clear and interactive view of sales performance. It effectively highlights trends, regional differences, and category contributions—meeting all requirements of Task 8.
