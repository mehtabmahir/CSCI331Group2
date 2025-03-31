 SQL Gamification Project 1
Team Members
- Nageen Saira
- Mehtab

Project Overview
In this project we created 7 unique cases involving fraud, error detection, data irregularities, and real-world business concerns. 
Tools & Databases
- SQL Server Management Studio / Azure Data Studio
- AdventureWorksDW2019, AdventureWorks2019, WideWorldImporter, Students Northwind
Case Investigations Summary

CASE 1: Employee Performance Tracking Database: AdventureWorks2019 Problem Statement: A company wants to evaluate employee performance using their pay history. Employees with a lower average pay rate may need support or training, while those with high pay are considered top performers. 
The company needs to: Identify employees with low average pay rates (below 20). 
Create a view that highlights top-performing employees with high rates (above 40). 
Provide a procedure to dynamically retrieve high-paid employees by passing a minimum rate threshold.
CASE 2: Fraudulent Transactions Detection
 Database: WideWorldImporters 
Problem Statement: The finance team at a bank suspects that some customers may be performing potentially fraudulent activities by making multiple high-value transactions in a short span of time. 
Identify individual transactions exceeding $10,000.
Detect customers who repeatedly make transactions over $5,000. 
Calculate a risk score for each customer based on Checked internal messages for discussion

CASE 3: Online Shopping Order Delays
Database: TSQLV6

Problem Statement:
An e-commerce company wants to analyze delivery performance. They are particularly concerned about delays in order delivery and want to identify patterns that can help improve logistics. They aim to:
Find orders that were delivered later than the required date.
Identify shippers (delivery partners) who are frequently associated with delayed deliveries.
Generate a delay report showing the number of days each delayed order was late.


CASE 4: Customer Purchase Behavior Analysis
Database: StudentNorthwinds
Problem Statement:
Instead of traditional student grading, this case explores customer purchasing habits in the retail context. The business wants to:
Identify customers who have spent less than $500 in total purchases.
Group customers based on their overall spending into categories: Low Value, Moderate, and High Value.
Retrieve a list of loyal customers who have placed more than 5 orders.
CASE 5: Inventory Management and Stock Depletion Forecast
Database: WideWorldImporters
Problem Statement:
A warehouse manager wants to proactively manage product inventory by identifying items that are low in stock and those frequently running out. The goal is to:
List products with current stock levels below 50 units.
Track frequently out-of-stock items using a view.
Estimate how long current stock will last using a user-defined function that calculates depletion time based on historical usage.
CASE 6: Sales Discount Analysis
Database: AdventureWorks2019
Problem Statement:
The sales department wants to analyze how discounts influence customer purchasing behavior. The team is particularly interested in customers who consistently receive high discounts and how discount thresholds affect sales performance. The tasks include:

Identifying individual sales transactions where the unit price discount is 20% or more.
Using a CTE to calculate the average discount per customer, and identifying those who average at least 15%.
Using a subquery to find customers who received a high discount (20% or more) in more than 3 orders.
Creating a stored procedure to dynamically retrieve transactions above a given discount threshold.

 CASE 7: Popular Picks & Missing Viewers
Database: ContosoRetailDW
Problem Statement:
A streaming-like analytics platform wants to analyze product "view" behavior (simulated using online sales data). Customers represent users, and products represent streamed content. The team wants to:
List the most-watched products based on total order frequency.
Identify inactive users (customers who haven’t ordered anything in the last 3 months).
Use a function to calculate the average quantity (watch time) per customer.
Create a view to highlight trending products that are viewed more than 50 times.

 ARTICLE: The Strength of SQL in a Python-Dominated World
In a world where Python dominates data science, SQL is often underrated. However, this article highlights that SQL remains a powerful and essential tool for structured data analysis. Unlike Python’s flexible, general-purpose nature, SQL is purpose-built for querying relational data efficiently. While Python offers versatility through its libraries, SQL’s strength lies in its simplicity, speed, and readability when working with databases. The article emphasizes that success in data work comes from knowing when to use SQL for its efficiency and when to switch to Python for more complex tasks—showing that both languages are stronger together, not in competition.
