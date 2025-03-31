Nayem Sarker README.md Answers - 


1. This query retrieves all sales invoice lines from March 2016 using the WideWorldImporters database. It joins invoice, line, and customer tables and orders results by lowest line profit to identify underperforming sales.

2. Using the AdventureWorks2019 database, this query identifies all sales orders from January 2014 that included a discount. It joins sales orders with salespeople and employees to show who authorized each discounted sale.

3. This query creates a scalar function that calculates total quantity changes for any product in the transaction history. It’s then used to display transactions with their corresponding total quantity impact for 2014.

4. This query extracts all `ALTER_TABLE` schema change events from the DatabaseLog table for May 2023. It provides insight into which user made the changes, the affected table, and the exact SQL used.

5. This query identifies schema changes made in October 2017 and summarizes which user made the most table modifications. It uses a CTE and aggregation to highlight potential unauthorized or bulk changes.

6. This query analyzes employee pay rate changes in December 2011 and cross joins with a list of managers to simulate approval relationships. It's designed to investigate anomalies like unusually high pay rates compared to peers.

7. This script defines an inline table-valued function to filter schema changes by month and year. It enables modular querying of ALTER_TABLE events for audits, demonstrated with October 2017 as an example.
