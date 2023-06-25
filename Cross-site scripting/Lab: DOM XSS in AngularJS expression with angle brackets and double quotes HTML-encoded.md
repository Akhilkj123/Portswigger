- Consider a shopping application that contains a DOM-based cross-site scripting vulnerability in a AngularJS expression within the search functionality.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/7d0f169b-3091-4a35-a0e2-9d387e211c00)

- Now we enter some random values in the searchbox.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/2bcc7eaf-d4f1-4152-b879-cd7e4f8389cf)

- We inspect the page source and get to know that these strings are being saved in 'ng-app' tag.

  ![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/1d86df5a-de2b-4aa3-be4c-0eccb4adf436)

- Now we inject our payload into the script by entering it in searchbox.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/1ed47f77-a7b3-4ed1-a38f-35ee524d0919)

- This makes the alert box appears and the lab gets solved.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/fded1e65-3bd4-4ede-aefe-89e80282b9f0)

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/af41f075-bfab-4da7-b79f-a571d4da70da)
