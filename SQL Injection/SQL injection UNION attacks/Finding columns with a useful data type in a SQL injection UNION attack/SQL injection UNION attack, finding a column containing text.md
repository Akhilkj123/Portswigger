We are here to conduct a SQL Injection UNION attack that returns an additional row containing the value provided. For that we have 2 key requirements 
- we have to determine the number of columns
- we should identify which column is compatible to string data

![image](https://user-images.githubusercontent.com/65653010/235028927-86f63a63-3ddb-4a6d-8cbc-861d0afb707d.png)

From this we get that the page contain three columns,

![image](https://user-images.githubusercontent.com/65653010/235029188-964d2f18-f7b5-4346-bde3-e31fb1c5efc7.png)

Next we have to determine which column is compatible with string data. When we try a column, it is not compatible and it gives an error.

![image](https://user-images.githubusercontent.com/65653010/235029844-433962c7-4aad-44ac-8e22-651f6e77af30.png)

Now we get that the 2nd column is compatible with string data 

![image](https://user-images.githubusercontent.com/65653010/235031500-8d391b7a-074a-43e8-a5ae-a3e3ac710685.png)

Now we add our data to it

![image](https://user-images.githubusercontent.com/65653010/235031989-4da7e2c1-53c8-45c7-bd68-06f2f99cefea.png)

