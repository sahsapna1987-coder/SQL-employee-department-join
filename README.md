## Project Overview
This project demonstrates how SQL `JOIN` operations combine relational tables in **Google Big Query* to audit employee assignment and department staffing.
## Query Output
![BigQuery Full OUTER JOIN Results](Screenshot%202026-11-21%2022434.png)
## Key Findings
* ** INNER JOIN: ** Matched 5 active employee with their assigned departments (`Marketing` and Engineering`).
* ** Full OUTER JOIN :* Uncovered that ** Mary Martin ** (Receptionist) had an unmapped `department_id` (null`), and that **Accounting* and **Sales** currently have no listed employees.
## Tools Used
* Google Big Query
* SQL (`SELECT`, `AS` aliases, `INNER JOIN`, FULL OUTER JOIN`)  

