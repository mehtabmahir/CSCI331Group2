KETAN PERSAUD:
Case 1) you create 2 joins that allow you to get the name, jobtitle, email, and passwordhash. we use the where clause to match the description given.
Case 2) you create a join that gets you the customer ID and the Stock Item ID. Then we use the information given in our where clause that the persons ID was 14 and that it happened in 2014 for the month of january. 
Case 3) you create a join that gets the name and vacation hours. Using the given information that the person needed at least 48 hours to make the trip we put in the where clause that they need at least 48 vaction hours.
Case 4) you create 2 joins that allow you to get the name, job title, and employee pay bonus. We want the top of the of the table so we use top(1). Then we single out all the non married people and order in descending order of the bonus so that we get the highest bonus.
Case 5) you create an intersection between the purchase order IDs in purchase orders and purchase order lines. Then from that intersection we exclude any order that has been finalized.
Case 6) you create a join so that we can get the state name and the person's address. Then we put the affected area into the where clause to get the addresses of those affected.
Case 7) you create a table that we use in our where clause. the table intersects employees and job candidates to see who got hired. then we just get their names. 
