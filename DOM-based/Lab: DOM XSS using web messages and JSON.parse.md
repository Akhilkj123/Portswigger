- Consider a shopping application uses web messaging and parses the message as JSON.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/81925caa-dfeb-4875-b5aa-38f72e4a3c86)

- We solve this lab by construct an HTML page on the exploit server that exploits this vulnerability and calls the print() function. In this application home page contains an event listener that listens for a web message. This event listener expects a string that is parsed using JSON.parse().

