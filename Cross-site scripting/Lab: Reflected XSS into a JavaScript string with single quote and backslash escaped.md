- Consider a shoppping application that contains a reflected cross-site scripting vulnerability in the search query tracking functionality

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/61b41222-d19f-4dae-b89e-d314dd08b5fe)

- We perform a cross-site scripting attack that breaks out of the JavaScript string and calls the alert function. First we give a random value in the searchbox and capture it using BurpSuite.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/25ec5e13-11ec-4b30-8c60-1de69b201fb5)

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/b5a628cf-8da8-4dc0-b04c-b743254363f4)

- Now we try sending the payload test'payload and observe that our single quote gets backslash-escaped, preventing us from breaking out of the string.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/8a890944-0872-4666-9d98-89f4664d36fd)

- Now we input with the following payload to break out of the script block and inject a new script.

  ![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/18281e90-e455-42b0-99e7-106f2ea830f4)

- This results in a alert box and the lab gets solved.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/7ae06361-538d-4c10-aae7-46fd6d03d6d4)

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/37a90db7-0472-4753-8514-d34a2f113114)


