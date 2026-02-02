# Day-27 SQL ORDER BY LIMIT.

Overview

On Day 27, I focused on two important SQL clauses used to sort data and control result size. These are commonly used in analytics queries, dashboards, and reports.

Topics Covered

1. ORDER BY
Used to sort query results in ascending or descending order.

SELECT * FROM employees
ORDER BY salary ASC;

SELECT * FROM employees
ORDER BY salary DESC;

By default, sorting is ASC (ascending).

⸻

2. LIMIT
Used to restrict the number of rows returned.

SELECT * FROM employees
LIMIT 5;


⸻

3. ORDER BY with LIMIT
Commonly used together to get top or bottom records.

SELECT * FROM employees
ORDER BY salary DESC
LIMIT 3;


⸻

Learning Outcome
	•	Learned how to sort query results
	•	Understood how to fetch top or limited records
	•	Improved ability to write efficient SQL queries

⸻

