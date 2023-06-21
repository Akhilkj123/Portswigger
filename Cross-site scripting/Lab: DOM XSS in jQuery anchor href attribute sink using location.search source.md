- Consider a shopping application that contains a DOM-based cross-site scripting vulnerability in the submit feedback page.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/2ab503b2-0e15-4b61-9b96-37a36c6ae191)

- It uses the jQuery library's $ selector function to find an anchor element, and changes its href attribute using data from location.search.
- Now we enter into the 'Submit Feedback' page

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/bc980977-d3f4-4b57-9518-8394f5ede2d7)

- We see the URL contains a return path option with value '/'

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/535f5248-1629-4f3d-9551-7b7ebbdc7f23)

-  When we give a random value the return path section we get a the value which is saved in the href

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/bf58a060-b5c0-41b3-aba0-088c7a34f67b)

- So now we are going to give the alert statement in the return path value which creates an alert and the lab gets solved.

  ![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/484362ec-1e9a-4d2a-a470-5627fe68b74f)

