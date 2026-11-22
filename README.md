## Project Overview
This project demonstrates how SQL `JOIN` operations combine relational tables in **Google Big Query** to audit employee assignment and department staffing.
## Query Output
<img width="1329" height="621" alt="Screenshot 2026-11-21 224234" src="https://github.com/user-attachments/assets/a385cb15-abc9-4701-b29b-f776c6126395" />

## Key Findings
* **INNER JOIN:** Matched 5 active employee with their assigned departments (`Marketing` and Engineering`).
* **Full OUTER JOIN:** Uncovered that **Mary Martin** (Receptionist) had an unmapped `department_id` (null`), and that **Accounting** and **Sales** currently have no listed employees.
## Tools Used
* Google Big Query
* SQL (`SELECT`, `AS` aliases, `INNER JOIN`, FULL OUTER JOIN`)  

