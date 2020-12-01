## GROUP BY Clause
The SQL GROUP BY Clause is used to output a row across specified column values.  It is typically used in conjunction with aggregate functions such as SUM or Count to summarize values.  In SQL groups are unique combinations of fields.  Rather than returning every row in a table, when values are grouped, only the unique combinations are returned.

The DISTINCT modifier stops at outputting a unique combination of rows, whereas, with the GROUP BY statement, we can calculate values based on the underlying filtered rows for each unique combination.

## COUNT
The COUNT function is used when you need to know how many records exist in a table or within a group.  COUNT(*) will count every record in the grouping; whereas COUNT(expression) counts every record where expression’s result isn’t null.  You can also use Distinct with COUNT to find the number of unique values within a group.

## MIN and MAX
Use MIN and MAX to find the smallest and largest values, respectively, within a table or group.

## HAVING Clause
The HAVING clause is used to filter groups according to the results of the aggregate functions.  This makes it possible to solve problems such as select all orders that have more than two order detail lines.

## Normalizing Data
Normalizing, separate the data into a Student and Classes table.   This makes it really easy to update the student name, but the price for this is that we have to piece the data back together to answer most of the questions we ask the database.

