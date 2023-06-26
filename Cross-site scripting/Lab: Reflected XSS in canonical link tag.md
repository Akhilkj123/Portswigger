- Consider a shopping application which reflects user input in a canonical link tag and escapes angle brackets.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/141160e4-1816-4f4b-bcd8-d7396f9b4aaf)

- We perform a cross-site scripting attack on the home page that injects an attribute that calls the alert function. Now we inject a URL to the page with our lab ID. 

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/5e7b537a-3343-4438-9463-6d425f201fd1)

- This sets the X key as an access key for the whole page. When we press the access key(ALT+SHIFT+X), the alert function is called and thus the lab gets solved.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/9cb7f7d8-8fd7-409e-88cd-927902f44849)


