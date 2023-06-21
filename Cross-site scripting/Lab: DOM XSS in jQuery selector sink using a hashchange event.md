- Consider a shopping application that contains a DOM-based cross-site scripting vulnerability on the home page.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/cdca4615-e8c5-4fb3-a619-48526dcfc262)

-  It uses jQuery's $() selector function to auto-scroll to a given post, whose title is passed via the location.hash property.
-  So we need to create an exploit to the victim in the print() section. For that we go to the exploit server.

  ![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/78f9be5a-e25a-4b0c-a89f-c65faacb3775)

- Now we add a malicious iframe to the body section

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/d330ec88-4adf-4c2e-8bc6-4933e6436c69)

- Now we store the value and will view the exploit

 ![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/1ed57be7-62c3-476e-ac1a-2d5dee75ab9c)

  ![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/0adbd773-c977-48b8-8fe5-d1508545d253)

- Now let us go back to the exploit server and deliver the exploit to the server.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/b695f498-3c75-4bac-9e6b-48ed189c3aaf)




  
