# Labwork 2: Relational Algebra
**Source:** `2. Relational Algebra.pdf`

## 1. Schema
Consider this schema:
* `employees(emp_no, birth_date, first_name, last_name, gender)`
* `departments(dept_no, dept_name)`
* `dept_emp(emp_no, dept_no, from_date, to_date)`
* `dept_manager(dept_no, emp_no, from_date, to_date)`
* `titles(emp_no, title, from_date, to_date)`
* `salaries(emp_no, salary, from_date, to_date)`

## 2. Requirements
Write relational algebra expressions for the following queries *(use a pen and paper...)*:

1. All info of all employees
2. All info of all departments
3. Full names of all employees
4. Names of all departments
5. Full names of employees working in `"ICT"` department
6. Full names of male employees working in `"BIO"` department
7. Salaries of female employees working in `"WEO"` department
8. Full names of employees who have the same last name as their manager
9. Full names of employees who was paid more than $\$100000$
10. Names of all departments that have employees paid more than $\$1000000$