# Sales-Perfomance-Dashboard:
Interactive sales performance dashboard built with HTML, CSS, JavaScript and Chart.js. Features KPI cards, dynamic filters (date, city, category, sales rep), 9 interactive charts, top/bottom product insights and drill-down detail pages. Responsive and loads data from Excel/CSV.
Sales Performance Dashboard | FY 2025
A modern, interactive, web-based sales dashboard (similar to a Power BI / Tableau report) built with HTML, CSS and JavaScript using Chart.js and SheetJS. Everything is in one file: Sales_Dashboard_2025.html.
Features:
KPI cards: Total Sales, Total Profit, Total Orders, Average Order Value
Charts: City-wise sales (bar), Category-wise performance (pie), Sales Rep performance (bar), Monthly sales trend (line)
Advanced insights: Profit vs Sales by product, Discount impact on profit margin (bar), Payment method distribution (pie), Top 5 and Bottom 5 products by sales
Filters: Date range, City, Category, Sales Rep. All charts update dynamically.
Drill-down details page: click any KPI card or chart to open a full details page (large chart plus breakdown table). The red Close button, the Esc key or the browser Back button returns to the dashboard.
Hover tooltips with detailed values (sales, profit, orders, margin)
Responsive layout for desktop and mobile
Animation: dashboard, raw data wipe, dashboard fade-in (use "Replay animation")
How to run:
Download Sales_Dashboard_2025.html and double-click it (internet needed once for the Chart.js and SheetJS CDN libraries).
The 2025 sales data is already built in, so it works immediately.
To use another file, click Load Excel / CSV and choose a file with these columns: Order_ID, Order_Date, Customer_Name, City, Region, Product_Category, Product_Name, Sales_Rep, Units_Sold, Unit_Price, Total_Sales, Payment_Method, Discount_%, Profit
Host it on GitHub Pages
Rename the file to index.html, push it to a repository, then Settings > Pages > deploy from the main branch.
