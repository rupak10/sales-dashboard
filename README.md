# Sales Dashboard (Power BI)

## Overview
- Interactive sales dashboard built in Power BI to summarize orders, customers, and product performance.
- Data sources: [Details.csv](Details.csv) and [Orders.csv](Orders.csv).

## What’s included
- Key metrics: Total Sales, Total Profit, Total Quantity, Average Order Value, Top Customers
- Visuals: Time series (sales by month), category breakdown, division breakdown, top division/customer lists, and trend KPIs.
- Filters: Quarter, Division

## Screenshot
![Final dashboard screenshot](<power bi sales dashbaord e-commerce.png>)

## Open and run
1. Open Power BI Desktop.
2. File → Open → select the .pbix report for this project (if present) or start a new report.
3. In Home → Get Data → Text/CSV, load:
   - [Details.csv](Details.csv)
   - [Orders.csv](Orders.csv)

## Notes
- Ensure the relationship between Orders and Details is correct (OrderID primary/foreign key).
- Validate date columns are set to Date type for proper time intelligence.

## License
- No license specified. Add one if required.