- Consider a shopping application with a DOM-based redirection vulnerability that is triggered by web messaging.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/2a1f79e5-ccef-407b-afba-3076c0be4e33)

- We construct an HTML page on the exploit server that exploits this vulnerability and calls the print() function. In this the home page contains an addEventListener() call that listens for a web message. For that we go to the exploit-server.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/7215a019-3ddd-4e2d-8f11-434fcbd60c89)

- Now we add the following iframe to the body.

 ![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/2b72aff7-f1af-4f58-9d9e-5da3792b71b9)

- Now we store the value and deliver it to the victim

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/007149e8-e2ee-418d-8b1b-1676326e6422)

- So the lab gets solved.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/fc3e4e1a-c763-4a59-8657-bfd032879b47)



