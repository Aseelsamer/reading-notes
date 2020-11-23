## What is SQL?
SQL, or Structured Query Language, is a language designed to allow both technical and non-technical users query, manipulate, and transform data from a relational database. 


-To retrieve data from a SQL database, we need to write SELECT statements, which are often colloquially refered to as queries. 
-In order to filter certain results from being returned, we need to use a WHERE clause in the query. The clause is applied to each row of data by checking specific column values to determine whether it should be included in the results or not.
-the DISTINCT keyword will blindly remove duplicate rows, you can know how to discard duplicates based on specific columns using grouping and the GROUP BY clause.
-When inserting data into a database, we need to use an INSERT statement, which declares which table to write into, the columns of data that we are filling, and one or more rows of data to insert.
-When you need to delete data from a table in the database, you can use a DELETE statement, which describes the table to act on, and the rows of the table to delete through the WHERE clause.
-When you have new entities and relationships to store in your database, you can create a new database table using the CREATE TABLE statement.
-In some rare cases, you may want to remove an entire table including all of its data and metadata, and to do so, you can use the DROP TABLE statement, which differs from the DELETE statement in that it also removes the table schema from the database entirely.