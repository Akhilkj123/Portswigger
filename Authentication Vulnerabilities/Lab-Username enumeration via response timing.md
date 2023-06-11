- Consider a shopping application which is vulnerable to username enumeration using its response times.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/39ace0d6-c004-464a-968a-9c05e4343a81)

- Now we capture the page which we entered some random usernames and passwords

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/03e55125-3a11-47b7-a465-44d6b3b7befd)

- Now we add an header 'X-Forwarded-For' , which allows us to spoof our IP address and bypass the IP-based brute-force protection.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/76d2d6c3-040c-49ab-af3e-0d543e1f54c6)

- Now give the x-forwarder value as payload and the second username value as the other payload in the intruder to retrieve the username as

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/378ec315-ad2a-4afe-90b4-3b0a4045600a)

- This is the username which takes an extra response time to get completed
- Now when we brute-force the password we get







