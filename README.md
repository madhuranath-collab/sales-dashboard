# 📊 Sales Data Analysis Power BI Dashboard
## 📁 Project Overview
This Power BI project analyzes sales data from a retail company using a star schema model. The analysis covers performance metrics such as top/bottom product sales, discounts, sales trends over time, and comparisons across various categories and time periods. The report provides interactive dashboards that help stakeholders make informed business decisions by visualizing key KPIs and trends.

## 🗂 Data Model
The dataset follows a star schema with the following structure:

Fact Table:

Contains transactional sales data (Sales, Profit, Quantity, Discount, Order ID, Dates, etc.)

Dimension Tables:

Customer Dimension Table:

Customer ID, Customer Name, Email, State, City, Contact Number

Product Dimension Table:

Product ID, Product Name, Price, Product Type (e.g., Electronics, Footwear, etc.)

Promotion Dimension Table:

Promotion Name, Discount Offered, Promotion Category

All dimension tables are connected to the Fact Table via one-to-many relationships.

## 📈 Dashboard Summary
The report consists of 4 dashboards, each covering a specific analytical requirement:

### 📌 Dashboard 1 – Overview Dashboard
Map Visual: Displays sales distribution across various cities.

KPI Card: Shows total number of orders (e.g., 3510).

Bar Chart: Shows average discount value in each promotion category.

Scatter Plot: Visualizes relationship between net sales and profit.

Line Chart: Displays net sales trends over time (daily, yearly).

### 📌 Dashboard 2 – Top/Bottom Products Analysis
Top 5 Products: By Sales, Profit, and Quantity Sold

Bottom 5 Products: By Sales, Profit, and Quantity Sold

### 📌 Dashboard 3 – Time Period Comparison
Interactive date slicers allow users to select two different periods.

Visuals dynamically compare Sales, Profit, and Quantity Sold across selected periods.

### 📌 Dashboard 4 – Filtered Analysis
Dynamic filters by:

Product Name

Customer Name

Promotion Category

Date

Detailed table displays all fields like:

Sales, Profit, Discount, Net Sales, and other metrics per order.

### ✅ Business Requirements & Their Implementations
Requirement	Implemented?	Description
1. Top/Bottom 5 product by Sales/Profit/Quantity Sold	✅	Implemented in Dashboard 2
2. Sales trends over time (daily/monthly/quarterly/yearly)	✅	Line chart in Dashboard 1; Time intelligence available
3. Relationship between Sales & Profit	✅	Scatter plot in Dashboard 1
4. Compare metrics between any two time periods	✅	Dual slicer implementation in Dashboard 3
5. Average discount offered by category	✅	Bar chart in Dashboard 1
6. Total number of orders	✅	KPI card in Dashboard 1
7. Show full order details with visual filters	✅	Dashboard 4 includes full filtering with all relevant fields
8. Show sales by different cities	✅	Map visual in Dashboard 1

## ⚙️ Key Features
📍 Location-based insights using map visuals.

📅 Temporal filtering and comparison using date slicers.

🎯 Promotion performance tracking based on discount category.

🔄 Dynamic filtering by Customer, Product, Promotion, and Date.

📊 Comprehensive data visuals including bar charts, scatter plots, and line graphs.

📌 Clean and responsive design for business usability.

## 📌 Tools Used
Power BI Desktop

DAX (for calculated columns and measures)

Data Modelling using Star Schema

Custom Visuals (e.g., map, slicers, scatter charts)
