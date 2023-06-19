- Consider a shopping application that contains a DOM-based cross-site scripting vulnerability in the search query tracking functionality.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/da2a8136-8de1-418e-baca-9b65fea1c6e8)

-  It uses the JavaScript document.write function, which writes data out to the page. The document.write function is called with data from location.search, which you can control using the website URL.

- Now we enter the 'hi' statement in the search box.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/92492783-a13d-496a-982d-5785f84ff836)

- Now we inject our vulnerability in the search box

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/561f8456-4653-4f02-ae3b-5a0b4be58f97)

- This results in the alert box to appear and the lab gets solved

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/32d6249b-3485-4c4f-8a7c-1ad73ac7a92f)

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/587952a2-7afb-4373-9144-4b1093b647a1)
