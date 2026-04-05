📊 Superstore Sales Excel Dashboard

Tools: Microsoft Excel · Pivot Tables · Dashboard Design
Dataset: 9,800 US orders · $2.26M total sales · Superstore (domestic)
Goal: Build an interactive sales analysis dashboard using Excel pivot tables

📌 Project Overview

This project demonstrates building a complete Excel analytics workbook from a raw sales dataset — without any external tools. All analysis was done using Excel's built-in capabilities: pivot tables, calculated columns, formulas, and chart-based dashboards.

📊 Analysis Sheets Built

Sheet	Analysis
rev_by_seg	Revenue by customer segment (Consumer · Corporate · Home Office)
rev_by_cat	Revenue by product category (Technology · Furniture · Office Supplies)
rev_by_region	Revenue by region (West · East · Central · South)
rev_by_seg&cat	Cross-analysis: Segment × Category with Ship Mode filter
rev_by_region&cat	Cross-analysis: Region × Category
Dashboard	Visual chart dashboard

🔢 Key Numbers

Metric	Value
Total Sales	$2,261,537
Top Segment	Consumer ($1,148,060 · 51%)
Top Category	Technology ($827,456)
Top Region	West ($710,220)
Total Orders	9,800

🛠️ Excel Techniques Used

Pivot Tables — summarised sales across multiple dimensions
IF + AVERAGE formula — created Aboove_Avg flag column (marks orders above dataset average)
Nested IF — created Value_Tier column (Low / Medium / High) based on sales amount
Group by Months — time-series breakdowns in pivot tables
Ship Mode filter — used as slicer across the Segment × Category analysis
Table Formatting — applied Excel Table format to raw data for dynamic pivot range
Chart Dashboard — built from linked pivot charts

💡 Insights

Consumer segment accounts for 51% of all orders but not proportionally higher average order value
Technology is the highest-revenue category; Furniture and Office Supplies are close behind
West region leads in total revenue; South region is the smallest market
Potential to target Corporate and Home Office segments — both are currently below Consumer share

📁 Files in this repo

File	Description
train.xlsx	Full workbook with all analysis sheets and dashboard
README.md	This file
dashboard.png
