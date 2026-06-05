# Accounts-Payable-Analytics-Dashboard
An interactive Power BI dashboard built to analyze accounts payable data across multiple vendors, currencies, and payment statuses.
Overview
This dashboard provides a comprehensive view of AP operations, including vendor payment analysis, invoice status tracking, overdue invoice monitoring, and monthly payment trends.
Key Metrics

267 overdue invoices identified
30 days average payment cycle
5 vendors tracked: BluePrints, ABC Supplies, Global Office, TechMart, Fast Travel
5 currencies analyzed: AUD, GBP, USD, CAD, EUR

Dashboard Components

Sum of Amount by Vendor — identifies highest-spend vendors
Currency Distribution — pie chart showing payment breakdown by currency
Invoice Status — count of Paid, Open, and Partial invoices
Monthly Trend (2023–2025) — invoice amount over time
Overdue Invoices — DAX-calculated count of unpaid past-due invoices
Avg Payment Days — DAX measure calculating average invoice-to-due-date cycle

Tools Used

Power BI Desktop
DAX (Data Analysis Expressions)
Microsoft Excel (data source)

Dataset
Source: Accounts Payable Dataset — Kaggle
