- Consider a shopping application that has a stock check feature which fetches data from an internal system.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/35b0420d-f306-4fb7-8f12-3de2502720f3)

- Now we visit a product, click "Check stock", intercept the request in Burp Suite, and send it to Burp Repeater.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/57f28297-ebe6-4bd0-b86f-f229983c4e4c)

- Now we change the URL in the stock api parameter

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/465b558f-2a97-4d6a-bedc-f0fb191eb3f2)

- Now we change the URL to 'http://127.1/admin' and observe that the URL is blocked again.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/4d73ba25-d15b-48ad-8636-dd9c43b9a511)

- We try buy obfuscating the first letter with URL encoding

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/126f1939-d8de-4394-8073-ec2ffc466e62)

- As we get the admin privilege we delete the user carlos

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/32944c9f-1fb4-40a7-a6b7-cd084a9901dd)
