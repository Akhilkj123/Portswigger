- Consider a shopping application that contains a DOM-based cross-site scripting vulnerability in the search blog functionality.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/793083f8-8926-45f7-baea-c8bea3a90e12)

- It uses an innerHTML assignment, which changes the HTML contents of a div element, using data from location.search.
- Now we inject the image tag in the search box

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/4f61f750-3ada-46a7-9575-549fe76e839e)

- So we get a alert box into it and the lab gets solved

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/dfde5c79-ac04-49c7-8bf9-75858bd6d69f)

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/2d59b58b-0e77-4116-8f38-0dd3d1be280f)

