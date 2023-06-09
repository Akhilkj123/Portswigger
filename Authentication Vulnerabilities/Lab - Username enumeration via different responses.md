- Consider a shopping application which is vulnerable to username enumeration and password brute-force attacks.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/ffa2b3cc-444f-47c7-ab23-cc42ddbbd46c)

- Now login to the with some credentials

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/f943578d-8adc-472b-b925-ff65ea81168f)

- Now we will capture it using BurpSuite

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/d482c9a3-9946-47a1-8428-f2a57adc0851)

- Then we will send it to the intruder and give the username to brute-force and give the payloads as the provided usernames

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/60fb8bbe-9d51-444f-bcc9-760aacfdc0de)

- Now we got the length as different

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/d0020647-b9f3-43b4-8f33-a8c76f038b6c)

- Now we change the username before brute-forcing the password

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/3f177f21-a542-4128-a73d-b7c9d234265a)

- Now we got the password 

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/0cd3b3f5-6def-48dd-bb39-b55c0cc4c33b)

- With the obtained credentials we login to the shopping application







