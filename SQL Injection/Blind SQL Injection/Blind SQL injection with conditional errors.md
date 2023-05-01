![image](https://user-images.githubusercontent.com/65653010/235434927-8133c83b-8edb-46ae-9149-10b67bad8007.png)

![image](https://user-images.githubusercontent.com/65653010/235435143-e6d6eeab-a04e-47e4-9a2d-e75c50be614a.png)

In this case, notice that the query still appears to be invalid. This may be due to the database type - try specifying a predictable table name.

![image](https://user-images.githubusercontent.com/65653010/235435254-9ff3cf89-2fff-421f-9f06-26bec01f2a89.png)

 This indicates that the target is probably using an Oracle database, which requires all SELECT statements to explicitly specify a table name. 
 
 ![image](https://user-images.githubusercontent.com/65653010/235435547-7ee5345b-f44f-4785-8689-09f572b4c297.png)

![image](https://user-images.githubusercontent.com/65653010/235435603-bbfa0e31-55e2-4b83-a754-8339aca39cf5.png)

 We use a query to check whether the username administrator exists

![image](https://user-images.githubusercontent.com/65653010/235435722-cf682a1c-509e-4a4d-8473-b681f9abb9b1.png)

We have verified the condition is true (the error is received), confirming that there is a user called administrator.

The next step is to determine how many characters are in the password of the administrator user. To do this we query

![image](https://user-images.githubusercontent.com/65653010/235435927-5406b143-492c-43b3-9658-2838f7e15871.png)

WHen error comes, we understood that the password length is not 1. Similarly, wev proceed the query til we get the length of the password

![image](https://user-images.githubusercontent.com/65653010/235436116-40ccf351-99b9-46d6-b74d-bc3a92b31b30.png)

![image](https://user-images.githubusercontent.com/65653010/235450720-d0b7c3d8-4a20-467a-a9ef-814e31d531fc.png)


![image](https://user-images.githubusercontent.com/65653010/235450688-80e28f68-5637-4c37-98cd-6b2349bcf884.png)


