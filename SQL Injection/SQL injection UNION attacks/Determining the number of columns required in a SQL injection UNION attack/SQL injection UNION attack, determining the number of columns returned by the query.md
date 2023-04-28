We are going to perform a SQL Injection to determine the number of columns present in a SQL Injection vulnerable webpage

![image](https://user-images.githubusercontent.com/65653010/235019004-81a6ee63-38c1-4436-9d57-bee54e86e47b.png)

This shows a shopping website with category="Corporate+Gifts"

Here, the actual query is

SELECT * FROM someTable WHERE category = 'Coroporate+Gifts'

We modify the query to

SELECT * FROM someTable WHERE category = 'Gifts' UNION SELECT NULL--
  
 which shows that internal server error, which determines that the table does not contain only one column
![image](https://user-images.githubusercontent.com/65653010/235020460-8b570a67-20dc-491d-a776-79a2f40e5aed.png)

  Similarly, we continue the query for two columns and atlast at three columns the query gives the result and the page shows all the results from the table 

![image](https://user-images.githubusercontent.com/65653010/235021319-2211fd15-84d4-41df-9ec7-51ab9c31e2fe.png)
