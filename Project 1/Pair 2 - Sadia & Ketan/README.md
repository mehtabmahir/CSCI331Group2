[Link to Pair Video)(https://drive.google.com/file/d/13fkKL1OWlx0Eo1uyk20AC8h_Nkjrl_N_/view?usp=sharing)

### SADIA SHARMIN'S CASES:

Case 1) Used joins to combine the invoices, customers, cities, and state provinces tables. Then, extracted any row that did not have a confirmed delivery time to see similarities and differences between the orders.

Case 2) Using the customers and customer transactions tables, we looked at the customer information, their credit limit, and the total outstanding balance for rows where the credit limit was null.

Case 3) Joined the orders table with the customers table and then looked at the customers whose last order date was before 2016.

Case 4) CTE was used to get a list of customers' information and their order counts. Then from that list, we selected any customer that has at least 20 orders.

Case 5) Joined the people table with the orders table to get the employee's name and the number of orders they worked on. From there, we looked at orders from May 2015 to July 2015, and focused on the employees that had a total order count of less than 600.

Case 6) Using the people table, we looked at the people that were employees and did not have a logon or hashed password associated with their name.

Case 7) Joined the customers and invoices table onto the orders table to look at orders that had an expected delivery date more than one day after the order date. Also looked at other information about the order, such as the customer and delivery method.

Medium Profile: @sadia.sharmin45

[Link to Medium Article](https://medium.com/learning-data/5-mistakes-i-made-at-my-first-data-analyst-job-2a44361a29d2)

This article discusses the writer's experience at their first data analyst Job. As someone considering potentially working in the same field, the article was very insightful. The writer discussed some mistakes they made at their first job, such as trying to learn everything at once, or not knowing how to prioritize tasks, and then provided some suggestions on how to avoid those challenges. By keeping those ideas in mind, hopefully, I will be able to avoid similar mistakes.

### KETAN PERSAUD'S CASES:

Case 1) you create 2 joins that allow you to get the name, jobtitle, email, and passwordhash. we use the where clause to match the description given.

Case 2) you create a join that gets you the customer ID and the Stock Item ID. Then we use the information given in our where clause that the persons ID was 14 and that it happened in 2014 for the month of january. 

Case 3) you create a join that gets the name and vacation hours. Using the given information that the person needed at least 48 hours to make the trip we put in the where clause that they need at least 48 vaction hours.

Case 4) you create 2 joins that allow you to get the name, job title, and employee pay bonus. We want the top of the of the table so we use top(1). Then we single out all the non married people and order in descending order of the bonus so that we get the highest bonus.

Case 5) you create an intersection between the purchase order IDs in purchase orders and purchase order lines. Then from that intersection we exclude any order that has been finalized.

Case 6) you create a join so that we can get the state name and the person's address. Then we put the affected area into the where clause to get the addresses of those affected.

Case 7) you create a table that we use in our where clause. the table intersects employees and job candidates to see who got hired. then we just get their names. 

Medium:https://medium.com/my-games-company/a-game-dev-recruiter-shares-how-to-prepare-for-an-hr-interview-8468f2c2916e
