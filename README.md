# SQL-Labs
This project contains SQL practice exercises using MariaDB. The queries focus on selecting, filtering, and analyzing data with clauses such as WHERE, BETWEEN, LIKE, and NOT. Screenshots and examples are included to demonstrate how to extract meaningful insights from database tables.

# Step 1
![WHERE AND](https://github.com/Dai05/SQL-Labs/raw/13dfa7a22409a0f25676a75cceb899b6c83f770a/where-and.png)

There was a potential security incident that occurred after business hours (after 18:00). All after hours login attempts that failed need to be investigated.
The following code demonstrates how I created a SQL query to filter for failed login attempts that occurred after business hours.

The first part of the screenshot is my query, and the second part is a portion of the output. This query filters for failed login attempts that occurred after 18:00. First, I started by selecting all data from the log_in_attempts table. Then, I used a WHERE clause with an AND operator to filter my results to output only login attempts that occurred after 18:00 and were unsuccessful. The first condition is login_time > '18:00', which filters for the login attempts that occurred after 18:00. The second condition is success = FALSE, which filters for the failed login attempts. 

# Step 2
