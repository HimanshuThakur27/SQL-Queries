# SQL-Queries
# SQL Practice Queries

This repository contains my SQL practice solutions covering fundamental and intermediate SQL concepts.

## Topics Covered
- SELECT
- WHERE
- ORDER BY
- GROUP BY
- HAVING
- JOINS (INNER, LEFT, RIGHT)
- Aggregate Functions
- Subqueries
- Constraints
- Table Creation

## Sample Queries

### Find all employees with salary greater than 50000
```sql
SELECT * FROM Employees
WHERE Salary > 50000;
```

### Count employees in each department
```sql
SELECT Department, COUNT(*)
FROM Employees
GROUP BY Department;
```

### Inner Join Example
```sql
SELECT e.Name, d.DepartmentName
FROM Employees e
INNER JOIN Departments d
ON e.DepartmentID = d.DepartmentID;
```

This repository showcases my SQL learning and hands-on practice.
