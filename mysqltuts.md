MySQL
Introduction
User -> DBMS (manages commands) -> DB (store)
Market
MySQL
SQL Server (Microsoft)
Oracle
Types
Relational
Tables linked with each other
Use SQL
Non-Relational(No SQL)
Tables not linked with each other
No SQL cannot understand SQL
Install from mysql.com
Notes
SQL not case sensitive
Queries
USE
USE - Select Database
USE <database name>;
SELECT- Columns
SELECT <*> -  all columns
SELECT <column name 1>, <column name 2>
SELECT <expression  or formula using existing column data> AS <name new column> 
SELECT DISTINCT <column name> - Gets us unique value in columns /Does not duplicate
FROM- Table Names
FROM <table name>
WHERE - Specific Query using Value or to filter data
WHERE < column name> = '###"
WHERE <expression 1> AND <expression 2>
WHERE NOT (birth_date > '1990-01-01' OR points > 3000)
WHERE state IN ('TX', 'NY', 'VA') or NOT IN ('TX', 'NY', 'VA') 
WHERE points BETWEEN 1000 AND 3000
WHERE address LIKE '%trail' OR address LIKE '%avenue'
WHERE address REGEXP 'trail' 
WHERE last_name REGEXP '[gim]e' - gives last name with ge, ie, me
WHERE first_name REGEXP 'elka|ambur'
WHERE last_name REGEXP 'ey$|on$'
WHERE last_name REGEXP '^my|se'
WHERE last_name REGEXP 'b[ru]' 
WHERE phone IS NULL
ORDER BY - Sort Columns
ORDER BY <Column Name>
LIMIT - Restrict Size
LIMIT 6, 3   (3 ROWS WILL BE SKIPPED, 3 will be checked)
JOIN -  combine rows from two or more tables, based on a related column between them. 
INNER JOIN OR JOIN - Returns records that have matching values in both tables. 
LEFT JOIN -Returns all records from the left table, and matched records from right table 
RIGHT JOIN -Returns all records from the RIGHT table, and matched records from LEFT table 
FULL JOIN - Returns all records when there is a match in either left or right table 
ON -  To specify arbitrary conditions or specify columns to join, the ON Clause is used. 
JOIN departments d ON (e.department_id = d.department_id);
