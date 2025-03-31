# Project 1 – CSCI 331 – Mehtab Mahir

This project simulates seven investigative data cases using T-SQL inside Azure Data Studio. 
Each case is built around a suspicious activity or anomaly, and uses SQL techniques to identify the problem, investigate the cause, and confirm the individual involved.

---

## Case 001: The Mystery of the Missing Inventory
We searched for inventory records missing on a specific date, simulated the disappearance using an INSERT, and tracked the suspect via a communication log.
[Watch Video](https://example.com)

### Steps:
1. Query inventory for the date of the incident.
2. Simulate the missing inventory using INSERT.
3. Look up employees.
4. Log and confirm a suspicious message.

---

## Case 002: The Data Breach Dilemma
We analyzed the password table to simulate compromised credentials and used communication logs to tie it to an insider.
[Watch Video](https://example.com)

### Steps:
1. Explore the password table structure.
2. Simulate credential misuse.
3. Identify a likely employee.
4. Add a communication message to confirm guilt.

---

## Case 003: The Vanishing Vehicles
High-value vehicles disappeared. We examined inventory and transaction history, simulated a withdrawal, and confirmed the responsible person.
[Watch Video](https://example.com)

### Steps:
1. Search for vehicles affected.
2. Simulate the theft in transaction history.
3. Use employee data to select a suspect.
4. Log a message confirming intent.

---

## Case 004: The Financial Fraud Firewall
An unexplained price increase occurred. We found no real change and simulated one, then traced it to a specific employee via logs.
[Watch Video](https://example.com)

### Steps:
1. Check for list price changes.
2. Simulate a fraudulent price hike.
3. Identify potential culprits.
4. Log a message to confirm the fraud.

---

## Case 005: The Silent Salesperson
We found a salesperson with no recent activity. Using OUTER APPLY, we examined their last transaction and confirmed they were ghosting work.
[Watch Video](https://example.com)

### Steps:
1. LEFT JOIN to find reps with no sales.
2. OUTER APPLY to find last transaction.
3. Log a performance-covering message.

---

## Case 006: The Vendor Kickback Scheme
We detected a vendor receiving too many orders. We used GROUP BY to find totals, tied it to an employee, and revealed a kickback scheme.
[Watch Video](https://example.com)

### Steps:
1. Group vendors by total purchase.
2. Match vendor to employee.
3. Confirm involvement via message.

---

## Case 007: The Fabricated Freight Fees
A fake order with inflated freight charges was created. We tracked it using a freight-to-subtotal ratio and confirmed manipulation via logs.
[Watch Video](https://example.com)

### Steps:
1. Query freight percentage over 20%.
2. Simulate a suspiciously high charge.
3. Log a communication that confirms fraud.
4. Join employee and communication data.

---

## Submission Notes
- Notebook: `Project1_CSCI331_MehtabMahir_WithStepExplanations.ipynb`
- Each case has full outputs and explanation cells.
- Videos will be linked here when uploaded.



---

## Acknowledgments

While solving these cases, I referenced the Medium article titled  
**"Gamifying SQL: Solving Mysteries with AdventureWorks"** (by Will Velida).

This article helped me:
- Understand how to simulate real-world fraud and trace it via SQL
- Structure investigations around Inventory, Transactions, and CommunicationLogs
- Apply JOINs, CTEs, and OUTER APPLY in practical forensic scenarios

The cases in this project were inspired and guided by the structure and spirit of that article.
