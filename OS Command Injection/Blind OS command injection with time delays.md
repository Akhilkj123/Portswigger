- Consider a shopping application which contains a blind OS command injection vulnerability in the feedback function.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/83e67f52-768a-4b04-a3f9-f914cc1dd05c)

- The application executes a shell command containing the user-supplied details. The output from the command is not returned in the response.
- Now we edit the email section in the feedback section

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/b8d48392-a14d-409d-8022-58bc3e8a6991)
 
 - Now if we give a ping command it gets a 10 seconds delay to respond which clarifies that the command we give in working.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/dda54c0a-ffda-4f97-a69f-20a57d547495)

- Which gives the lab complete

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/075f12af-7a08-4ba5-89c1-1a05ca5785b5)



