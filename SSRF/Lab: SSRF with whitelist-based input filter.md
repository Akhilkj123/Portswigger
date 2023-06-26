- Consider a shopping application that  has a stock check feature which fetches data from an internal system. 

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/8596447d-b44b-4bd6-8f84-eec1dc3bc049)

- We solve this lab by change the stock check URL to access the admin interface at http://localhost/admin and delete the user carlos. Now we visit a product, click "Check stock", intercept the request in Burp Suite

