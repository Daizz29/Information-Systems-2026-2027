# Labwork 3: Structured Query Language (SQL)
**Source:** `3. SQL.pdf`

## 1. Setup
* Use the installed `employees` database.
* Write SQL queries and use `mysql` command line tool to test previous relational algebra expressions.

## 2. Requirements

### Part 1: SQL Queries
Write the SQL queries to get the following information:
1. All info of all employees
2. All info of all departments
3. Full names of all employees
4. Names of all departments
5. Full names of employees working in `"Sales"` department
6. Full names of male employees working in `"Finance"` department
7. Salaries of female employees working in `"Marketing"` department
8. Full names of employees who have the same last name as their manager
9. Full names of managers who have been doing the job at least twice
10. Full names of employees who was paid more than $\$100000$
11. Names of all departments that have employees paid more than $\$100000$

### Part 2: Database Modification
Due to changes in company's organization, the following departments are merged:
* **Development (`d005`)** and **Research (`d008`)** $\rightarrow$ **Research and Development (`d010`)**
* **Marketing (`d001`)** and **Sales (`d007`)** $\rightarrow$ **Marketing and Sales (`d011`)**

Write necessary SQL queries to implement these changes to the `employees` database.