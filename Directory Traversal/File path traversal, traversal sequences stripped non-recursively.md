- Consider a shopping application with Directory Traversal Vulnerability.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/eec67952-094c-46d2-9b4b-a33720487976)

- Now this application has stripped or blocked '..' and '/'  i.e directory traversal direct bypass user-supplied filename, then it is possible to bypass the defense using  variety of techniques. 
- Now we are going to edit the filename in the application.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/46435143-5ae7-43e3-9062-2e575885b72a)

- We give the filename as a combination of '....' and '//'. So, if the application strips '..' or '/' additional '..' and '/' available which gives the result.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/3ff0c72a-bcf0-4034-bd03-01f55bb6e8df)

- So, we get the result of lab solved.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/c571653b-35f9-4194-83d4-32081c3517c4)
