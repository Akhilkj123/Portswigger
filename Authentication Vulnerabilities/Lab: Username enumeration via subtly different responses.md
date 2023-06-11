- Consider a shopping application which is subtly vulnerable to username enumeration and password brute-force attacks. 

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/5c0dc876-4e9c-480c-b800-c836b72ad8c5)

- Now login to the application using invalid username and password

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/da84ad7e-b978-45cb-9286-823b08833a7c)

- Now we capture the login page ,with invalid credentials, using Burpsuuite and sent it to Intruder.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/c86cbc85-35ba-4641-bd9c-b35dab975644)

- Now we sent it to Burp intruder and highlight the username and add a extra 'grep-extra' in settings and highlight the 'invalid username or password'.
- Now we start brute-forcing and get a different output.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/f7248b1e-638e-4be6-aa20-68d7489f6e00)

- The value does not contain any '.', which shows it is the username.
- Now give the username as payload and retrieve the password

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/61804a82-e1fd-495a-b301-253412d3efe5)

- This result of the password shows no warning, so this is the password. Now we login to the account using retrieved username and password and the lab gets solved

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/c0b8fdc5-1cdb-4faf-a065-995b649ed486)
