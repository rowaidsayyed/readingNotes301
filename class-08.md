# Welcome 301d4
## What is SQL?
SQL, or Structured Query Language, is a language designed to allow both technical and non-technical users query, manipulate, and transform data from a relational database.

## Relational databases
relational database represents a collection of related (two-dimensional) tables. Each of the tables are similar to an Excel spreadsheet, with a fixed number of named columns (the attributes or properties of the table) and any number of rows of data.
## Select queries
To retrieve data from a SQL database, we need to write 'SELECT' statements
A query in itself is just a statement which declares what data we are looking for,

## Queries with constraints
In order to filter certain results from being returned, we need to use a 'WHERE' clause in the query.

## Filtering and sorting Query results
 SQL provides a convenient way to discard rows that have a duplicate column value by using the 'DISTINCT' keyword.
### Ordering results
SQL provides a way to sort the results by a given column in ascending or descending order using the 'ORDER BY' clause.
### Limiting results to a subset
Another clause which is commonly used with the 'ORDER BY' clause are the 'LIMIT' and 'OFFSET' clauses.
The 'LIMIT' will reduce the number of rows to return, and the optional 'OFFSET' will specify where to begin counting the number rows from.
The 'INNER JOIN' is a process that matches rows from the first table and the second table which have the same key
* might see queries where the 'INNER JOIN' is written simply as a 'JOIN'

### Multi-table queries with JOINs
Tables that share information about a single entity need to have a primary key that identifies that entity uniquely across the database.
Using the 'JOIN' clause in a query, we can combine row data across two separate tables using this unique key.

#### Database normalization
Database normalization is useful because it minimizes duplicate data in any single table

### OUTER JOINs
If the two tables have asymmetric data, then we would have to use a 'LEFT JOIN', 'RIGHT JOIN' or 'FULL JOIN'


## INSERT,Updating ,Deleting rows

## Dropping,Altering and Creating