SQL Gamification Project: Data Detective Work with SQL 
This project applies SQL to identify anomalies, suspicious patterns, and potential fraud through data analysis.
Team Members
Mst Rahi
Nayem
Project Overview
This project is part of our SQL coursework designed to simulate real-world data investigations using SQL queries. Each case represents a realistic business scenario involving fraud, manipulation, or system errors. We analyzed each case using SQL on datasets like AdventureWorksDW and WideWorldImporters.
This README summarizes the 7 cases that my partner gave me, and I worked on, including their objectives, business context, SQL strategy, and key findings.
Databases & Tools Used
- AdventureWorksDW2019
- SQL Server Management Studio / Azure Data Studio
- T-SQL
The 7 Cases:
CASE #1: The Phantom Purchase Order: Investigated a large order logged with no inventory movement.
Goal: Trace the order, check inventory match, and find the responsible employee.
SQL Actions: Queried purchase orders by date, joined with inventory, employee, and vendor tables. Flagged orders with no inventory activity.

CASE #2: The June 15 Sales Spike: A massive and unexplained spike in online sales was flagged.
Goal: Determine if the sales spike was real or manipulated.
SQL Actions: Filtered internet sales on June 15, joined product and territory tables, and identified responsible salespersons.

CASE #3: Late-Night Order Edits: Orders were being modified late at night, suggesting unauthorized activity.
Goal: Find edits outside work hours.
SQL Actions: Pulled orders, joined editors' data, and filtered by time. Flagged suspicious timestamps.

CASE #4: Low-Profit Mug Sales: Mugs sold with extremely low profits and odd tax values.
Goal: Flag mug sales with profit < $30 and tax > $5.
SQL Actions: Pulled sales on Jan 7, 2013, filtered for mugs, joined employee and geography, and added case-based flags.

CASE #5: The Bubble Wrap Switcheroo: Sudden switch in product type, especially bubble wrap.
Goal: Detect abrupt product changes by employees.
SQL Actions: Used OUTER APPLY to trace previous product sold before each bubble wrap sale.

CASE #6: Hat Buyers Gone Wild: Customers were abusing a branded hat promotion.
Goal: Detect customers who bought an excessive number of hats.
SQL Actions: Counted hat purchases by customer and flagged high-volume or high-frequency buyers.

CASE #7: Weird Tax & Freight Charges: Final charges didn’t match tax or shipping standards.
Goal: Catch incorrect totals and mismatched tax/freight entries.
SQL Actions: Calculated expected tax and freight, compared with actuals, and flagged mismatches.

 “SQL Queries That Will Surprise You!” by Lakhveer Singh Rajput (CodeX)
In this engaging and insightful article, Lakhveer Singh Rajput introduces readers to a set of advanced and lesser-known SQL techniques that can transform the way developers and analysts think about data manipulation. The article covers practical challenges such as:

Finding the second highest or nth highest salary without using LIMIT/OFFSET
Identifying missing values in numeric sequences
Calculating running totals and cumulative sums with window functions
Pivoting rows into columns using CASE and aggregate functions
Detecting duplicates and overlapping date ranges
Traversing employee-manager hierarchies with recursive CTEs
Generating random test data and calculating medians



This project helped us think critically about data, spot anomalies, and apply SQL beyond textbook examples. Each case sharpened our analytical thinking, query-writing, and real-world data sleuthing skills.


