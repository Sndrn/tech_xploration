# HackerRank Certification

![sql](https://user-images.githubusercontent.com/89401289/171036293-88cce25e-10a3-46ec-af8c-3f4dc97ee14e.png)

### What is SQL?
- SQL stands for Structured Query Language
- SQL lets you access and manipulate databases
- SQL became a standard of the American National Standards Institute (ANSI) in 1986, and of the International Organization for Standardization (ISO) in 1987

### What Can SQL do?
- SQL can execute queries against a database
- SQL can retrieve data from a database
- SQL can insert records in a database
- SQL can update records in a database
- SQL can delete records from a database
- SQL can create new databases
- SQL can create new tables in a database
- SQL can create stored procedures in a database
- SQL can create views in a database
- SQL can set permissions on tables, procedures, and views

# What I've learned
To retrieve data from a database
## Major commands
For this certification I learned to use the following commands on existing databases in order to get an expected output (extracted data) from precise instructions & conditions :

### SELECT 
Extracts data from a database (columns)

### FROM 
Identify the name of the table

### WHERE 
The WHERE clause is used to filter records. It is used to extract only those records that fulfill a specified condition.
The following operators can be used in the WHERE clause:
- "="	Equal	
- ">"	Greater than	
- "<"	Less than	
- ">="	Greater than or equal	
- "<="	Less than or equal	
- "<>"	Not equal. Note: In some versions of SQL this operator may be written as !=	
- "BETWEEN"	Between a certain range	
- "LIKE"	Search for a pattern	
- "IN"	To specify multiple possible values for a column

### AND, OR and NOT Operators
The WHERE clause can be combined with AND, OR, and NOT operators.

The AND and OR operators are used to filter records based on more than one condition:
- The AND operator displays a record if all the conditions separated by AND are TRUE.
- The OR operator displays a record if any of the conditions separated by OR is TRUE.
The NOT operator displays a record if the condition(s) is NOT TRUE.

### ORDER BY
The ORDER BY keyword is used to sort the result-set in ascending (ASC) or descending (DESC) order.

### MIN() and MAX() Functions
The MIN() function returns the smallest value of the selected column.
The MAX() function returns the largest value of the selected column.

### LIKE Operator
The LIKE operator is used in a WHERE clause to search for a specified pattern in a column.

There are two wildcards often used in conjunction with the LIKE operator:
- The percent sign (%) represents zero, one, or multiple characters
- The underscore sign (_) represents one, single character

### BETWEEN Operator
The BETWEEN operator selects values within a given range. The values can be numbers, text, or dates.
IT is inclusive: begin and end values are included.

### INNER JOIN Keyword
The INNER JOIN keyword selects records that have matching values in both tables.

### GROUP BY Statement
The GROUP BY statement groups rows that have the same values into summary rows, like "find the number of customers in each country".

The GROUP BY statement is often used with aggregate functions (COUNT(), MAX(), MIN(), SUM(), AVG()) to group the result-set by one or more columns.

### HAVING Clause
The HAVING clause was added to SQL because the WHERE keyword cannot be used with aggregate functions.
