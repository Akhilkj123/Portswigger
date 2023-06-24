- Consider a shopping application which contains a reflected cross-site scripting vulnerability in the search blog functionality where angle brackets are HTML-encoded.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/c528483c-35d2-4aa7-8a13-900a551a8e6a)

- Now add some string in the search box and capture this page using BurpSuite.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/c7601fed-dd40-4496-8f15-b6e6da3b853c)

- Now we add the payload and inject it into the search box

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/4be07880-060e-4d35-b792-c2f5f5d191e4)

- We perform a cross-site scripting attack that injects an attribute which calls the alert function and gets the lab solved.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/a77aaceb-2751-418f-858d-0b18dbb2d21b)

  
