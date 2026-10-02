# Employee Management System – SQL Project

## Team Members
- Bharat J
- Kushal K
- Saiteja L

A MySQL Employee Management System designed as a practical SQL learning and portfolio project.

## Tables
- `departments`
- `employees`
- `projects`

## Concepts Demonstrated
DDL, DML, DQL, constraints, aggregate functions, GROUP BY, HAVING, joins, self join, subqueries, correlated subqueries, EXISTS, ANY, ALL, UNION, UNION ALL, CTEs, window functions, CASE, COALESCE, views, stored procedures, stored functions, TCL and DCL.

## Files
- `employee_management_system.sql` – complete MySQL script
- `Employee_Management_System_Report.docx` – project report with commands and representative outputs

## How to Run
1. Open MySQL Workbench or MySQL CLI.
2. Open `employee_management_system.sql`.
3. Execute from the top.
4. Review the queries section by section.
5. DCL commands are commented because they require suitable privileges.
6. Destructive examples such as DROP/TRUNCATE/DELETE are commented where appropriate.

## Future Extension
For a full production-style project, add an `employee_projects` junction table to model the many-to-many relationship between employees and projects, then connect the database to a Java/JDBC application.
