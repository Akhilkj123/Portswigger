- Consider a shopping application with file path traversal vulnerability in the display of product images. 

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/13ebd53c-3fdf-4d9f-aef5-24e4782c6ef1)

- The application transmits the full file path via a request parameter, and validates that the supplied path starts with the expected folder.
- Now we edit the filename of the application.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/f8389433-e68a-460c-a1df-f506a3c1dcbb)

- Since the application has implemented a rule to strictly add the file path of the images, we give a special techniques.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/57d2690a-804f-4587-bd37-47fe7c141f3d)

- We get the result and get the lab solved.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/5bc6ea8f-2e8c-44e9-b97e-ba6820e647be)



