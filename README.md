# Insurance Policy Analysis & Dashboard

## Project Overview
This project analyzes insurance customer and policy information using SQL, Excel, Power BI, and Tableau. It explores policy distribution, customer demographics, claims, premiums, and policy status, and presents the analysis through dashboards.

## Tools Used
- **MySQL** – querying and analyzing customer, policy, and claims data
- **Microsoft Excel** – data analysis, KPI tracking, and dashboarding
- **Power BI** – interactive dashboard and KPI visualizations
- **Tableau** – interactive data visualization

## Analysis Highlights
The SQL analysis includes:
- Total customers and total policies
- Total claim amount, average coverage amount, and average premium amount
- Active policy percentage and policy status distribution
- Active versus inactive policy ratio
- Policy counts by customer age group and gender
- Most and least common policy types
- Comparison of Auto and Health policies
- Yearly premium totals, premium growth rates, and policy-ending trends

## Repository Structure
```text
Insurance-Policy-Analysis/
├── SQL/
│   └── Insurance-Policy-Analysis.sql
├── Excel/
│   └── Insurance-Policy-KPI-Dashboard.xlsx
├── PowerBI/
│   └── Insurance-Policy-Dashboard.pbix
├── Tableau/
│   └── Insurance-Policy-Dashboard.twbx
└── README.md
```

## How to Explore
1. Open the SQL script in MySQL Workbench and run the queries against the project database.
2. Open the Excel workbook to explore the KPI analysis and dashboard.
3. Open the `.pbix` file in Power BI Desktop.
4. Open the `.twbx` file in Tableau Desktop.

> Note: The SQL script expects the database and tables referenced in the queries (including `CUSTOMERINFORMATION`, `POLICYDETAILS`, and `CLAIMS`) to be available. Update file paths or data connections in the dashboard tools if your local source files are stored elsewhere.

## Key Skills Demonstrated
SQL querying, joins, aggregate functions, CASE statements, CTEs, window functions, data analysis, KPI reporting, dashboard development, and data visualization.
