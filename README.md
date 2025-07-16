📊 Data Jobs Visualization - Power BI Dashboards
This repository contains two Power BI dashboards focused on job market analytics, designed to provide insights into job postings, required skills, and associated metrics. These reports are ideal for HR analysts, recruiters, or data professionals tracking hiring trends.

🧠 Highlights
⭐ Star Schema & Data Modeling
📊 Star schema data modeling enhances analytical power and efficiency:
Separating fact and dimension tables (e.g., job postings as facts, skills and companies as dimensions) simplifies relationships and enables complex queries like multi-skill job analysis—something flat tables cannot support well.

🧮 DAX Concepts
Calculated Columns vs. Measures vs. Calculated Tables

Writing DAX formulas for:
Aggregations: COUNT, SUM, MEDIAN
Logical conditions: IF
Understanding Contexts in DAX:
Row Context (lowest)
Query Context (medium)
Filter Context (highest precedence)
Using CALCULATE to manipulate filter context
Creating dynamic parameters for flexible "what-if" analysis

🎯 Parameters & Interactivity
Field Parameters: Switch among dimensions or metrics like job title, country, skills, or salary vs. job count
Numeric Parameters: Enable what-if analysis (e.g., salary/tax adjustments)
🧠 Empowers end users to dynamically control and customize visualizations

📊 File: pbi_job_data_visualization.pbix

📌 Features
🔘 Page navigation using custom buttons

📈 Diverse chart types for insights into:
    • Job availability
    • Salary distribution
    • Hiring trends
    • Skill requirements

⚡ Quick Measures for on-the-fly metric creation

🎨 Conditional Formatting to highlight job categories or roles

🔖 Bookmarks for saved views/actions

🔍 Drill-through functionality for deep-dives on selected job titles

⚡ Use of Quick Measures for on-the-fly calculations
🎨 Conditional Formatting to highlight job categories or roles
🔖 Use of Bookmarks for saved actions or views
🔍 Drill-through functionality for deep-dive analysis of selected job titles

🖼️ Visual Preview

<img width="1289" height="724" alt="Job Dashboard" src="https://github.com/user-attachments/assets/45e95675-c76f-42ad-a82f-017220f5136c" /> <img width="1290" height="728" alt="Skills and Salary View" src="https://github.com/user-attachments/assets/5fd8fb47-fc8f-4ccb-a211-2b29acd249b5" />

📊 File: Data Jobs Dashboard.pbix

📌 Features
📂 Using folder paths to implement delta load logic

🧼 Data cleaning with Power Query Editor

⭐ Building Star Schema through joins

➕ Adding Conditional Columns for data transformation

📎 Append Queries to handle multiple Excel sheets

🔗 Merge Queries to form relationships

✍️ Data transformation using Column from Examples

📋 Table creation using DAX

📊 Developing advanced measures for enhanced insights

📐 Application of Row, Query, and Filter Contexts

⚙️ Dynamic Parameters to switch axis fields (e.g., job_title, country, skills)

🖼️ Visual Preview
<img width="1176" height="662" alt="Delta Load Dashboard" src="https://github.com/user-attachments/assets/fd848c4c-cdae-4572-b38a-b52b698575f6" />
