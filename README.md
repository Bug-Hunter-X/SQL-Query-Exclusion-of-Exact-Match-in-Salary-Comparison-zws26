# SQL Query Bug: Greater Than Operator

This repository demonstrates a common SQL query error involving the `>` (greater than) operator.  The query is intended to select all employees in the 'Sales' department with salaries greater than 100000.  However, it unexpectedly excludes employees with salaries exactly equal to 100000.

The `bug.sql` file contains the erroneous query.  The corrected query, which includes employees with salaries equal to or greater than 100000, is in `bugSolution.sql`.