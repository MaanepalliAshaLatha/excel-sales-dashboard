📊 Superstore Sales Excel Dashboard<br>

Tools: Microsoft Excel, Pivot Tables, Dashboard Design<br>
Dataset: 9,800 US orders, $2.26M total sales, Superstore (domestic)<br>
Goal: Build an interactive sales analysis dashboard using Excel pivot tables.<br><br>

📌 Project Overview<br>

This project demonstrates building a complete Excel analytics workbook from a raw sales dataset without using any external tools. All analysis was performed using Excel's built-in features such as pivot tables, calculated columns, formulas, and chart-based dashboards.<br><br>

📊 Analysis Sheets Built<br>

• rev_by_seg – Revenue by customer segment (Consumer, Corporate, Home Office)<br>
• rev_by_cat – Revenue by product category (Technology, Furniture, Office Supplies)<br>
• rev_by_region – Revenue by region (West, East, Central, South)<br>
• rev_by_seg&cat – Segment × Category cross-analysis with Ship Mode filter<br>
• rev_by_region&cat – Region × Category cross-analysis<br>
• Dashboard – Visual chart-based dashboard<br><br>

🔢 Key Numbers<br>

• Total Sales: $2,261,537<br>
• Top Segment: Consumer ($1,148,060 · 51%)<br>
• Top Category: Technology ($827,456)<br>
• Top Region: West ($710,220)<br>
• Total Orders: 9,800<br><br>

🛠️ Excel Techniques Used<br>

• Pivot Tables to summarize sales across multiple dimensions<br>
• IF + AVERAGE formula to create the Aboove_Avg flag column<br>
• Nested IF to build the Value_Tier column (Low, Medium, High)<br>
• Group by Months for time-series analysis in pivot tables<br>
• Ship Mode filter used as a slicer for Segment × Category analysis<br>
• Table Formatting applied to raw data for dynamic pivot ranges<br>
• Chart Dashboard created from linked pivot charts<br><br>

💡 Insights<br>

• The Consumer segment contributes 51% of all orders.<br>
• Technology is the highest-revenue category; Furniture and Office Supplies follow closely.<br>
• The West region generates the highest revenue; the South region is the lowest.<br>
• Targeting Corporate and Home Office segments may unlock new growth opportunities.<br><br>

📁 Files in This Repository<br>

• train.xlsx — workbook with all analysis sheets and dashboard<br>
• dashboard.png — Image of dashboard
• README.md — documentation<br>
