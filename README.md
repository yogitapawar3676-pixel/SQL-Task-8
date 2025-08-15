# SQL-Task-8
Stored Procedures and Functions

##  Objective
The goal of this task is to learn how to create *Stored Procedures* and *Functions* in SQL to modularize and reuse database logic.

## Tools Used
- MySQL Workbench (You can also use DB Browser for SQLite, but syntax may vary)
- SQL Language

## What This Code Does
1. **Creates a database and an employees table**
2. *Inserts sample employee data*
3. *Creates a Stored Procedure* (IncreaseSalaryByDept) to update salary based on department
4. *Creates a Function* (GetAnnualSalary) to calculate an employee's annual salary

## How to Run
1. Copy the SQL script into your MySQL Workbench
2. Run the script step by step
   
## Key Concepts Learned
- *Stored Procedure*: Reusable SQL block for multiple operations
- *Function*: SQL block that returns a single value
- *IN Parameters*: Used to pass values into procedures/functions
- *Deterministic Functions*: Always return the same result for the same input

## Output Example
After running:
```sql
SELECT GetAnnualSalary(1);
