- Consider a shopping application which contains a reflected cross-site scripting vulnerability in the search query tracking functionality where angle brackets are encoded.

 ![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/f6506b37-59ca-43f4-9615-45d0711b1714)

- We are going to perform a cross-site scripting attack that breaks out of the JavaScript string and calls the alert function. First we are going to enter a random string in search box.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/c88ebfe6-2c2d-41ed-b61b-496e34743299)

- Now we are going to capture it using Burp.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/f7aefdca-8961-483c-b091-70e460732357)

- Now we enter our alert in the searchbox, which results in a alertbox.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/519e8359-d4e1-42cc-9eb9-a01faca304aa)

- This makes the lab solved

  ![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/c3ec59f6-3cd0-485b-834f-c62dd22e5708)

