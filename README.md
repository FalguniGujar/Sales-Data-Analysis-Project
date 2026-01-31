# Sales Data Analysis Dashboard
---
**🛠️ Tools Used**

Power BI | DAX | Power Query | CSV Dataset

**📌 Project Overview:**
This project focuses on building an interactive Financial Sales Analysis Dashboard in Power BI by performing data cleaning, transformation, data modeling, and advanced DAX-based analysis. The objective is to analyze sales performance, profit trends, discounts, and time-based comparisons to support business decision-making.

**🎯 Objective:**

To transform raw financial sales data into meaningful insights using Power BI and DAX, enabling analysis of sales, profit, discount patterns, and year-over-year performance.
🧹 Data Preparation (Power Query)
Imported dataset using Get Data from CSV
Opened Power Query Editor for transformation
Verified and corrected data types for each column
Converted Units Sold from decimal to Whole Number
Cleaned and loaded the transformed data into Power BI

**🗂️ Data Modeling:**

Created a separate Date Table using CALENDARAUTO()
Added new columns using DAX:
Month Number
Month Name
Year
Established a Many-to-One relationship between the Date Table and the main sales table

**📊 Data Analysis with DAX:**

Created key performance measures:
Sales Amount
Profit
Discount Offered
Profit Margin

**⏳ Time Intelligence Analysis:**

Used DATEADD() and Date Table relationships to calculate last year metrics:
Sales Amount Last Year
Profit Last Year
Orders Last Year
Profit Margin Last Year
Discount Offered Last Year
This enabled year-over-year comparison of business performance.

**🔍 Key Insights:**

Sales follow clear monthly/seasonal trends.
Higher discounts reduce profit margin.
Few products drive most of the revenue (Pareto effect).
Some regions have high sales but low profit.
Sales increased year-over-year, but profit didn’t grow proportionally.
Units sold ≠ profitability.
Identified best products, months, and regions for decision-making.
