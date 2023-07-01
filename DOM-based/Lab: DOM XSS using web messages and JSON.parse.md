- Consider a shopping application uses web messaging and parses the message as JSON.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/81925caa-dfeb-4875-b5aa-38f72e4a3c86)

- We solve this lab by construct an HTML page on the exploit server that exploits this vulnerability and calls the print() function. In this application home page contains an event listener that listens for a web message. This event listener expects a string that is parsed using JSON.parse(). Now we go the exploit server.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/4633b608-f4b4-4bc0-9eb6-34ad67de5fad)

- Now we enter the iframe tag in the body of the exploit server

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/2badf73e-208b-437d-ba31-c9ec48828731)

- When the iframe we constructed loads, the postMessage() method sends a web message to the home page with the type load-channel. Now we store the value and deliver it to the victim. So the lab gets solved.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/964dfb09-ff1e-4127-a8c2-9e43f49da1f2)




