We are here to perform a SQL Injection UNION attacks that retrieve all usernames and passwords and to use that information to login to all users.

This shows a vulnerable web page

![image](https://user-images.githubusercontent.com/65653010/235033582-dbab3c8f-bf98-4052-bba7-bf4b64e2254c.png)

We add the query 
SELECT * FROM someTable WHERE category = 'Gifts' UNION SELECT NULL username||'~'||password FROM users 

![image](https://user-images.githubusercontent.com/65653010/235034895-e2fc749c-e3e6-4690-9c56-fc89dfa28d29.png)

which retrieves all the usernames and passwords. Now, we use the retried username and password of the administrator to login to the site as administartor.

![image](https://user-images.githubusercontent.com/65653010/235035948-57fc969d-2d25-4c7d-ba88-9afd15693019.png)
