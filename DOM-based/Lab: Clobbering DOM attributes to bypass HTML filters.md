- Consider a shopping application uses the HTMLJanitor library, which is vulnerable to DOM clobbering.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/edc2abd8-d407-498c-9f30-f71a4effd72e)

- We solve this lab by constructing a vector that bypasses the filter and uses DOM clobbering to inject a vector that calls the print() function. Fo that, we go to one of the blog posts and create a comment containing the following HTML

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/be84b665-24de-467b-8359-6c390c961bd2)

- The comment gets submitted

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/dbf387d5-3e10-46c2-b287-6cdd332170db)

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/ce05dce6-7d75-40e4-9b7a-700ab24a9988)

- Now we go to the exploit server and add the following iframe to the body

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/8073c247-0bc6-48e9-bf72-169cb7b44c04)

- Thus the exploit gets delivered  to the victim and the lab get solved.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/81ac10d8-e43e-4dfc-9af9-2ae0f4de9ff4)

 
