- Consider a shopping application which has an admin panel at /admin, which identifies administrators using a forgeable cookie. 

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/e8f80eba-f5cb-4875-b92e-9d39038d50e5)

- Now we login to the application using the user wiener.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/a2305036-eb7a-40d8-9d84-97d9456fba4b)

- Now we have to capture it using burp, which shows admin=false

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/eec9dc89-a708-4581-9549-c27d6950ac2a)

- We now convert admin=true and go to the admin panel which gives

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/afb2ba67-a5cb-48fd-b2a0-25566fc344e3)

- Now when we capture the page using Burp and change the value of admin=true

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/3ba35b03-e7db-4814-8739-b5aed28260f6)

- It gives

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/dc763330-643f-4150-89f7-71a8ee134228)

- Now delete the user 'carlos' which gives the lab solved.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/54b48c17-037f-49a9-9118-cab7a77f0aea)










