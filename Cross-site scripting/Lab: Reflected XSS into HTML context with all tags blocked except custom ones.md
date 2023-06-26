- Consider a shopping application that blocks all HTML tags except custom ones.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/94fa74a2-881d-4c8c-85a5-991ce0530488)

- We perform a cross-site scripting attack that injects a custom tag and automatically alerts document.cookie. Now we go to the exploit-server in the application.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/cce853e6-4619-41ae-a8ed-1bac1be74f3e)

- Now we store the value and deliver it to the victim. This injection creates a custom tag with the ID x, which contains an onfocus event handler that triggers the alert function. 

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/d023e3fc-388a-4dee-a3ea-225933e98029)

- The hash at the end of the URL focuses on this element as soon as the page is loaded, causing the alert payload to be called. Thus the lab gets solved.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/84e0db63-6fcf-4cf2-9ff3-6e553e097b0e)


