- Consider a shopping application that demonstrates DOM-based client-side cookie manipulation.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/9599d852-4192-4003-9016-db92ca4eb11e)

- We solve this lab by injecting a cookie that will cause XSS on a different page and call the print() function. Now we go to the exploit server. 

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/c5bc536d-820a-44f3-9c0c-9ab93e86a4d9)

- In the exploit server we paste the iframe tag in the body section. The original source of the iframe matches the URL of one of the product pages, except there is a JavaScript payload added to the end. 

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/191d00e9-0458-4ce9-8372-103be3e631c0)

- Now we store the exploit and deliver it to the victim. So the lab gets solved. When the iframe loads for the first time, the browser temporarily opens the malicious URL, which is then saved as the value of the lastViewedProduct cookie.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/6b078b4a-a8c6-423b-a771-4f5a6af1a865)

