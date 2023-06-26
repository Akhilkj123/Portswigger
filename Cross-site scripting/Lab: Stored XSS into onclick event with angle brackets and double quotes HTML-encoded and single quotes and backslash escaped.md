- Consider a shopping application that contains a stored cross-site scripting vulnerability in the comment functionality.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/2a6ce603-5884-435c-86a0-73fb8343f4d0)

- We submit a comment that calls the alert function when the comment author name is clicked. Now we give some random string in the website section.

  ![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/b241562b-2536-4b01-9bf8-049c939ffb0b)

- We capture it using BurpSuite and we forward it

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/ab84e473-9dc7-4b70-9350-af5f06a55de0)

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/f70855e4-8412-4700-b1e4-28fabdd08c49)

- Now we  inject a JavaScript URL that calls alert, using the following payload.

  ![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/87656e73-54d5-400e-b7fb-5ebf62324ece)

- Thus the lab gets solved.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/91d6ee17-feaf-48ec-af7d-75b011b5a366)






