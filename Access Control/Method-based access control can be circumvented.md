- Consider a shopping application that implements access controls based partly on the HTTP method of requests.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/640334a8-e6f2-4359-9cbc-4979ab3063d7)

- Now we login to the application as administrator using admin credentials

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/d6cc54f2-25f7-4057-84f6-6ab22eab2cc1)

- Capture the page of admin panel using burp of logging in as admin

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/6f790bba-2a2f-4b6d-8376-ac5b3b1c5189)

- Now parallely take another window and login to the application as wiener using the credentials given

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/088e5d01-5d45-4f9d-9337-a7f3ed95674b)

- Capture the logged in page using BurpSuite

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/2adec3e4-ca95-46cd-8f1d-677e15983430)

- Copy and paste the session-cookies of the wiener to the first captured Burp page.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/7d36ca06-e73a-4e36-b54b-eda1d4665c0a)

- Now giving the option change the request mode and change the user name as wierner in the GET request

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/6afe1f78-7775-4296-ab90-9de0ee060900)

- Thus the lab gets solved

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/0f063f97-eaf8-47ab-b553-7ef94be152b8)





