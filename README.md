📊 Excel Dashboard – Sales & Customer Analytics
📌 Project Overview
This project showcases the design and implementation of an interactive Excel dashboard built to analyze sales performance, product trends, customer behavior, and time-series patterns using structured data modeling and Pivot-based analytics.
The dashboard transforms raw transactional data into actionable insights through optimized PivotTables, calculated measures, and synchronized slicer-driven interactivity.

🧱 Data Architecture
Source Data
Transaction-level dataset
Core fields:
Order Date
Product
Customer
Quantity
Sales
Cost
Profit
Data Design Principles
No hard-coded values in dashboards
All visuals driven by PivotTables
Standardized dimension values to avoid split aggregation
Numeric validation applied to all measures

📐 Metrics & Calculations
Key Measures
Total Sales – SUM aggregation
Total Profit – Derived as Sales − Cost
Quantity Sold
Customer Revenue Contribution
Product Performance Ranking
Calculation Controls
Profit aggregation explicitly set to SUM to avoid averaging errors
Date hierarchy used for time-series analysis
Duplicate dimension values handled at the source level

📊 Dashboard Components
1️⃣ Main Dashboard
Executive-level KPI overview
Product and customer performance summaries
Designed for quick decision-making

2️⃣ Time Series Dashboard
Sales trends over time
Seasonality and growth pattern analysis
Supports performance monitoring

3️⃣ Product Analysis
Product-wise sales and profit distribution
Identification of top and low performers
Supports pricing and inventory decisions

4️⃣ Customer Analysis
Customer segmentation by revenue contribution
Identification of high-value customers
Enables targeted business strategies

🎛 Interactivity & Controls
Slicers
Used for dynamic filtering across dashboards
Connected via shared Pivot Cache
Ensures synchronized filtering across PivotTables and PivotCharts
Known Limitation
Charts not based on PivotTables do not respond to slicers
All analytical visuals are Pivot-based by design

⚡ Performance Optimization
Minimal Pivot Caches to reduce recalculation overhead
Avoided volatile Excel formulas
Calculations handled within PivotTables rather than worksheets
Clear separation between data, analysis, and presentation layers

🔄 Refresh & Maintenance
PivotTables require manual refresh when source data is updated
No external data connections
Scalable design supports adding new data rows without rework

🛠 Tools & Technologies
Microsoft Excel
PivotTables & PivotCharts
Slicers
Data Modeling & Analysis
Business Intelligence Fundamentals

🎯 Intended Audience
Business stakeholders
Data analysts
Interview reviewers
Hiring managers assessing Excel analytics proficiency

👤 Author
Chandra Sekhar
Data Analyst
Skills: Excel | SQL | Power BI | Python
