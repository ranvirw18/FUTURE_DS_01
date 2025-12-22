📊 E-Commerce Sales Dashboard | Power BI

An interactive Power BI dashboard designed to analyze e-commerce sales performance across profit, quantity, categories, payment modes, states, and time.

This project focuses on correct business metrics, clean visuals, and practical DAX usage.

🔍 Project Objective

To provide a clear, decision-ready view of:

Overall profitability

Sales distribution by category and payment mode

State-wise and sub-category profit contribution

Monthly profit trends

Key performance indicators (KPIs)

📌 Key KPIs

Total Profit

Total Quantity Sold

Average Order Value (AOV)
(Calculated using proper DAX logic, not summed values)

📈 Dashboard Visuals

KPI Cards

Total Profit

Total Quantity

Average Order Value (AOV)

Donut Charts

Quantity by Payment Mode

Quantity by Category

Bar Charts

Profit by Month

Profit by State

Profit by Sub-Category

All visuals are interactive and respond to filters.

🧠 DAX Measures Used
Total Amount = SUM(Details[Amount])

Total Profit = SUM(Details[Profit])

Total Quantity = SUM(Details[Quantity])

Total Orders = DISTINCTCOUNT(Details[Order ID])

AOV = DIVIDE([Total Amount], [Total Orders])

🛠 Tools & Technologies

Power BI Desktop

DAX (Data Analysis Expressions)

Data Modeling

Interactive Visual Analytics

📂 Dataset Fields

Order ID

Amount

Profit

Quantity

Category

Sub-Category

Payment Mode

State

Order Date

(Transactional e-commerce sales data)

📷 Dashboard Preview

Replace dashboard.png with the actual screenshot file name from your repo.

✅ Key Learnings

Correct use of Measures vs Calculated Columns

Proper calculation of Average Order Value

Importance of aggregation context in Power BI

Designing dashboards based on business logic, not just visuals

🚀 Future Enhancements

Year-over-Year comparison

Profit margin %

Drill-through pages

Dynamic tooltips

Advanced slicers
