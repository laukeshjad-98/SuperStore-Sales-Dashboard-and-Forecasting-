# SuperStore-Sales-Dashboard-and-Forecasting
📊 SuperStore Sales Dashboard & Forecasting using Power BI
📘 Project Summary:

In this project, I designed and developed an interactive Power BI dashboard using the SuperStore Sales Dataset to analyze and visualize business performance metrics.
The goal was to identify sales trends, profit drivers, regional performance, and forecast future sales — helping decision-makers gain actionable insights from the data.

🧰 Tools & Technologies Used:

Power BI Desktop for data modeling and visualization

Power Query for data cleaning and transformation

DAX (Data Analysis Expressions) for creating key performance measures

Excel / CSV Dataset for raw data input

📌 Project Workflow:
✅ 1️⃣ Data Cleaning & Preparation (Power Query)

Removed duplicate and missing records

Corrected data types (Date, Number, Currency)

Renamed columns and standardized field names

Removed unnecessary fields to improve model performance

✅ 2️⃣ Data Modeling & DAX Calculations

Built DAX measures for key metrics such as:

Total Sales = SUM(SuperStore_Sales_Dataset[Sales])

Total Profit = SUM(SuperStore_Sales_Dataset[Profit])

Total Orders = DISTINCTCOUNT(SuperStore_Sales_Dataset[Order ID])

Profit Margin = [Total Profit] / [Total Sales]

Average Delivery Days = AVERAGE(SuperStore_Sales_Dataset[Ship Days])

Established relationships between tables for accurate filtering and drill-through analysis

✅ 3️⃣ Dashboard Development & Visualization

Designed a clean, interactive dashboard layout

Used visuals like:

KPI Cards (Sales, Profit, Orders, Ship Days)

Bar Charts (Category & Segment Performance)

Donut Chart (Region-wise Sales Contribution)

Line Chart (Monthly Sales Trend & Forecast)

Map Visual (State-wise Sales Distribution)

Added Slicers and Filters for Region, Segment, and Payment Mode to enhance interactivity

📊 Key Insights & Findings:

1️⃣ West Region generated the highest overall sales and profit.
2️⃣ Technology category was the most profitable, followed by Office Supplies.
3️⃣ Standard Class shipping had the highest number of orders but lower profit margins.
4️⃣ Sales showed a consistent growth trend, with peak performance in Q4 months.
5️⃣ Forecasting visual predicted a steady sales increase in upcoming months.

📈 Forecasting & Trend Analysis

Applied Power BI’s built-in forecasting model to estimate future sales trends.

Analyzed monthly patterns to predict future growth and identify seasonal fluctuations.

📌 Project Learnings (Good for Resume 📄)

Performed data cleaning and transformation using Power Query

Created and optimized DAX measures for business KPIs

Developed an interactive Power BI dashboard for business insights

Conducted time series analysis and forecasting

Improved data storytelling and visualization skills

📁 Project Files

Sales Dashboard & Forecasting.pbix → Power BI Dashboard File

SuperStore_Sales_Dataset.csv → Dataset used for analysis

README.md → Project Documentation

🚀 How to Use

1️⃣ Download or clone this repository
2️⃣ Open the .pbix file in Power BI Desktop
3️⃣ Load the dataset if prompted
4️⃣ Explore the dashboard and interact with slicers for insights

🏁 Final Conclusion

This project demonstrates how Power BI can turn raw sales data into actionable business insights.
Through interactive dashboards, it enables better understanding of regional trends, category performance, and future sales forecasts — supporting strategic business decisions.
