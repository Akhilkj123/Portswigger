- Consider a shopping application which has access to certain admin functionality based on the Referer header.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/93054254-cef1-4523-8499-5f2128dcced7)

- Now login as administrator using the credentials given

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/c32ee98d-d0f1-46d2-95ba-0e2eb7389c4f)

- Now capture the upgrade user page of carlos, we get /admin-roles?username=carlos&action=upgrade

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/b8b46df2-03c0-4769-b62a-ad00c3ddbed2)

- Now we login as normal user and capture the page

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/b2aa5813-976a-4210-a8bd-cfb90121ab2c)

- Paste the session cookie of normal user in the admin panel and change the username to wiener

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/7333ea01-4f5f-4929-9a34-9a4d121ad5ef)

- Thus the user wiener gets upgraded as admin and thus the lab gets solved

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/5f85ff88-fd64-4c36-94e8-4b6e8b6ef40f)
