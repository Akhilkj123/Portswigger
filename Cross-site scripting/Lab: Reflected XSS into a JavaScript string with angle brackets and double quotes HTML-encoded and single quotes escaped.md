- Consider a shopping application that contains a reflected cross-site scripting vulnerability in the search query tracking functionality where angle brackets and double are HTML encoded and single quotes are escaped.

  ![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/66e04a3b-3136-4b2e-802e-ed5cdfbe3936)

- Now we perform a cross-site scripting attack that breaks out of the JavaScript string and calls the alert function. We use some random alphanumericals in the searchbox.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/f71314b9-8667-4bd9-9948-8b73ee3aa235)

- Now we capture it using BurpSuite and check the script to see the random string in the script.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/693c3b0b-3918-43f8-bbe8-45d3f0810fc7)

- Now we try sending the payload test\payload and observe that our backslash doesn't get escaped.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/b59c46f6-d78c-49a1-ade9-ec5d151e90a7)

- Now we replace our input with the following payload to break out of the JavaScript string and inject an alert.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/357eef10-68b0-4c82-92b2-bf4d63d97c57)

- Thus it responds a alert box and the lab gets solved

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/6af4bc66-fdfd-4c76-85ff-2367d99e6568)

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/ebe429b1-b467-4117-bc41-b1c03c433dc5)
