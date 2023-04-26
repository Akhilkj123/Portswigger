**SQL Injection UNION ATTACKS**
- When an application is vulnerable to SQL injection and the results of the query are returned within the application's responses, the UNION keyword can be used to retrieve data from other tables within the database. 
- This results in a SQL injection UNION attack. 
-  The UNION keyword lets you execute one or more additional SELECT queries and append the results to the original query. For example:

SELECT a, b FROM table1 UNION SELECT c, d FROM table2

 It selects column and b from table1 and selects c and from table2. So both the queries are enquired at the same time using UNION.
 
 The key requirements for using UNION is that:
 - Same number of columns must be present in individual queries
 - Comapatible Data types must be present
