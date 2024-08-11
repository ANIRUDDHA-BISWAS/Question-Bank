## Question 1
Which SQL clause is used to filter rows before any groupings are made?
Time's up!
WHERE
SELECT
@ FILTER
@ HAVING

The quiz will continue 9 days ago

Explanation
‘The WHERE clause is used to filter rows before any groupings are made.

## Question 2
Which SQL clause is used to specify an alternative result if the condition of the
first SELECT statement is not met?

Time's up!
WHERE
EXCEPT
IF
ELSE

The quiz will continue 9 days ago

Explanation

The ELSE clause is used in conjunction with the IF-THEN-ELSE statement to
specify an alternative result if the condition of the first SELECT statement is not
met.

## Question 3
What is the primary purpose of the SQL HAVING clause?
Time's up!

To join tables
To rename columns in a result set
To filter groups after aggregation
To filter rows before grouping

The quiz will continue 9 days ago

Explanation
‘The HAVING clause is used to filter groups after an aggregation has been applied,
whereas WHERE filters rows before grouping.

## Question 4
Which SQL statement is used to change the structure of a table?
Time's up!

CHANGE

ALTER TABLE

UPDATE
MODIFY

The quiz will continue 9 days ago

Explanation

The ALTER TABLE statement is used to change the structure of an existing table,
such as adding, modifying, or dropping columns.The ALTER TABLE statement is
used to change the structure of an existing table, such as adding, modifying, or
dropping columns.

## Question 5
How do you remove a column named "Age" from an existing table "Persons"?
Time's up!

ALTER TABLE Persons REMOVE COLUMN Age;

UPDATE TABLE Persons DROP COLUMN Age;

DELETE COLUMN Age FROM Persons;
ALTER TABLE Persons DROP COLUMN Age;

The quiz will continue 9 days ago

Explanation
The correct syntax to remove a column is ALTER TABLE Persons DROP COLUMN,

Age;.

## Question 6
What will the following SQL statement do: SELECT * FROM Employees WHERE
Name LIKE '_a%'?

Time's up!

Select all employees whose names end with the letter ‘at
Select all employees whose names contain the letter ‘a’

Select all employees whose names havea as the second character
Select all employees whose names start with the letter ‘a’

The quiz will continue 9 days ago

Explanation
The _wildcard represents a single character, so _a% matches any name where ‘a
is the second character.

## Question 7
What is the result of a LEFT JOIN when there is no match in the right table?

Time's up!
Includes the row with NULL values for columns from the right table
Throws an error
Excludes the row from the result set
Duplicates the row

The quiz will continue 9 days ago

Explanation
ALEFT JOIN includes the row from the left table with NULL values for columns
from the right table when there is no match.

## Question 8
How can you select all records from a table named "Employees" where the
"Salary" is between 40000 and 60000? The most effective query?
Time's up!
SELECT * FROM Employees WHERE Salary >= 40000 AND <= 60000;
SELECT * FROM Employees WHERE Salary IN (40000, 60000);

SELECT * FROM Employees WHERE Salary IN RANGE (40000, 60000);
SELECT * FROM Employees WHERE Salary BETWEEN 40000 AND 60000;

The quiz will continue 9 days ago

Explanation
The correct syntax is SELECT * FROM Employees WHERE Salary BETWEEN 40000
AND 60000;.

