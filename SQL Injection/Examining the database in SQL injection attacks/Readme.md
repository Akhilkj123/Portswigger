This type of SQL Injection Attack includes the type and version of the database software, and the contents of the database in terms of which tables and columns it contains.

**Querying the database type and version**
- Different databases provide different ways of querying their version.

 The queries to determine the database version for some popular database types are as follows:
 
Database type 	      Query

Microsoft, MySQL 	  -   SELECT @@version

Oracle 	- SELECT * FROM  v$version

PostgreSQL -	SELECT version() 

you could use a UNION attack with the following input:

' UNION SELECT @@version--
