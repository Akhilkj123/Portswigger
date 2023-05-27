- Consider a shopping application which contains a blind OS command injection vulnerability in the feedback function.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/d038ae84-395c-4fcf-a3d8-c6e5dfb7b33a)

- The application executes a shell command containing the user-supplied details. The command is executed asynchronously and has no effect on the application's response. It is not possible to redirect output into a location that you can access. However, you can trigger out-of-band interactions with an external domain. 
- Now in this application we give a nslookup command with a burp created website.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/bf023a6b-629b-450f-bb3c-386d41fef268)


