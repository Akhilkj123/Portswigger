- Consider an application which contains a file path traversal vulnerability in the display of product images.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/002389a8-aaa4-4fbd-acd8-cbbf7bc4cefc)

- This application validates that the supplied filename ends with the expected file extension. 
- Now we are going to edit the filename of the application.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/6bac70bc-ed06-4cd0-8f15-a7c0a3915a0f)

- If an application requires that the user-supplied filename must end with an expected file extension, such as .png, then it might be possible to use a null byte to effectively terminate the file path before the required extension.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/2bc574b9-e5f2-46ae-b918-fb141b43b7bc)

- Now, we get the result and the lab gets solved.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/0cb51882-f9cc-4250-be68-d404f948d0cc)

