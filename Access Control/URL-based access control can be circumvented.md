- Consider a shopping application which has an unauthenticated admin panel at /admin.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/6a5c8808-e168-4021-aedb-21a60d52b425)

- Now we type /admin in the URL and will capture the page using Burpsuite

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/d2bab2f7-701b-44ff-8bd2-68a86adc859c)

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/6450a0a2-26ef-4ecb-b563-1a28168a67bf)

- Now we change the value of the X-Original-URL header to /admin

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/3bd4106a-2923-4a53-b4e4-74e4c4fe319d)

- Now we delete the user carlos, by adding ?username=carlos to the real query string, and change the X-Original-URL path to /admin/delete.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/75a77389-467d-4aad-b2da-32ce5580dd36)

- Thus the lab gets solved

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/0503f781-cdb3-414b-9dd9-423855fa923b)








