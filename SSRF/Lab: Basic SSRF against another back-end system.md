- Consider a shopping application that has a stock check feature which fetches data from an internal system.

 ![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/b7ddc7a3-4f36-4d2c-bab5-faae6d53ab19)

- We use the stock check functionality to scan the internal 192.168.0.X range for an admin interface on port 8080, then use it to delete the user carlos. So, Visit a product, click "Check stock", intercept the request in Burp Suite.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/02a01b14-d4a2-4c64-9462-48491d99bc9a)

- Now we send it to the Burp Intruder and retirve the correct IP

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/570ba997-b924-4158-aa4a-e6274d7d5a7d)

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/26891941-ba52-44ba-a2fd-084f8143f56d)

- Now we give it as the last octat which gives us the admin privilege.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/ea0092ad-50f6-4d7d-8e4f-1b8d17d460b1)

- Now we delete the user carlos and the lab gets solved.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/f3133d38-3074-4509-aafd-01f158ec940c)

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/d6fa1ce2-1b1a-4b4e-bab9-7263e6cfd5bb)

