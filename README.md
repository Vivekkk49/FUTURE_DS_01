# FUTURE_DS_01
1st Task for Data Science and Data Analytics. 
🔧 Tools Overview for "Madhav Ecommerce Sales Dashboard"

🟡 1. Microsoft Power BI
Primary Tool Used: For dashboard design, data modeling, and visualization.

🔑 Key Features Utilized:

📁 A. Data Import & Transformation
Tool Used: Power Query Editor

Data Source: Could be Excel, CSV, SQL Server, or local database
Cleaning Steps:
Removed null or duplicate records
Standardized column names (e.g., Amount, Profit, Quantity)
Converted data types (e.g., dates, numbers)
Extracted useful date fields (Month, Year)
Merged Tables: Joined Orders, Customer, Products, States if separate
📐 B. Data Modeling
Tool Used: Power BI Data Model View

Relationships:
One-to-many relationships between Customer ID, Product ID, State
Defined appropriate relationships for slicers and filters to work
Data Types:
Measures: Sum of Profit, Sum of Amount
Columns: State, Category, Payment Mode, etc.
🔢 C. DAX (Data Analysis Expressions)
Tool Used: Power BI’s DAX Formula Bar

Examples of DAX Measures:

Total Sales = SUM(Sales[Amount])
Total Profit = SUM(Sales[Profit])
Average Order Value = [Total Sales] / [Total Quantity]
Top 5 Categories = TOPN(5, VALUES(Product[Category]), [Total Sales])
✔ Used to:

Calculate aggregates
Create KPIs
Enable dynamic interactivity
Filter context-sensitive data (e.g., Monthly profit)
📊 D. Data Visualizations
Tool Used: Power BI Report View

Types of Charts Used:

Visualization	Purpose
KPI Cards	Show total values for amount, profit, etc.
Bar Chart (Horizontal)	Revenue by State, Profit by Sub-Category
Column Chart (Vertical)	Monthly Profit Trends
Donut Charts	Quantity by Category and Payment Mode
Stacked Column / Bar	Top customers by revenue
💡 Visual Formatting:

Used dark theme for high contrast
Labels and tooltips enabled
% values on pie charts
Slicers for City and Quantity filters
🔍 E. Filters & Slicers
Tool Used: Visual Slicers & Page Filters

Slicers for:
City (Ahmedabad, Amritsar)
Quantity (1, 2)
Allow users to dynamically filter data across the dashboard
🌐 F. Interactivity & Navigation
Enabled Features:

Drill-throughs: Click on a bar to see detailed customer/category info
Cross-filtering: Clicking a pie slice filters related visuals
Bookmarks (if used): For switching between views
📤 G. Publishing & Sharing
Tool Used: Power BI Service (cloud)

Published to Power BI workspace
Shared with stakeholders via link or embedded in web page
Refreshed regularly via scheduled refresh (if connected to SQL/Excel Online)
🧠 Final Insights

Strengths Enabled by Tools	Explanation
Data Clarity	Clean and structured data ensures accurate visuals
Performance Tracking	KPIs and trends help track goals
Customer Insights	Top customers by revenue help in loyalty marketing
Product Optimization	Profit by category helps stock and promote high-profit items
Payment Analysis	Know which payment method users prefer
Geographical Trends	Identify regions contributing most to sales
