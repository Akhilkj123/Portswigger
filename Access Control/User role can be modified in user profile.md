- Consider a shopping application with access control vulnerablitity

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/a34edc8b-605b-4112-b517-6212094009e0)

- Now let us begin by logging into the webpage using given credentials

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/bf11b0bb-b104-4ca1-b43a-a0f88745bc97)

- Now we add the email to the webpage

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/2c019a26-94b2-44d6-929f-93aefec29e06)

- Now we capture the email site using Burp and copy the roleid in our query

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/4c26a8a7-e2d4-4d8a-a817-629d4c78057c)

- Now we change the roleid to 2 which gets updated.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/60483c54-64f8-4c5a-803e-f2ee9be6aa31)

- Now we change the /my-account to /admin URL.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/5efcc020-76cb-4008-b363-eb5a6f37e984)

- Now we give the query of delete username 'carlos' which deletes the username. 

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/d868cd4f-09a2-43be-aae6-606eaa0c2da0)

- Thus the lab gets solved.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/15a33602-32ee-40a5-b877-2886bc8c0134)




