- Consider a shopping application that reflects our input in a JavaScript URL, but all is not as it seems.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/84d01b93-aeea-43a8-ad59-c75a9fdb85f9)

- We are going to perform a cross-site scripting attack that calls the alert function with the string 1337 contained somewhere in the alert message. We inject the URL 'https://YOUR-LAB-ID.web-security-academy.net/post?postId=5&%27},x=x=%3E{throw/**/onerror=alert,1337},toString=x,window%2b%27%27,{x:%27'

 ![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/7fb60dd8-2215-4d11-b42c-6e79a883b160)

- The exploit uses exception handling to call the alert function with arguments. We need to use arrow functions to create a block so that the throw statement can be used. Thus the lab gets solved.

 ![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/e4a4cab3-c9cf-41b5-b5b6-ae05256d67c9)
