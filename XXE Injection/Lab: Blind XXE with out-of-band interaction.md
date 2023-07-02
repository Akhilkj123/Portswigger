- Consider a shopping application that has a "Check stock" feature that parses XML input but does not display the result. We can detect the blind XXE vulnerability by triggering out-of-band interactions with an external domain. 

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/459fa9f7-b193-4b26-9e56-7c1c3a4f3a5d)

- We insert the following external entity definition in between the XML declaration and the stockCheck element. We replace the productId number with a reference to the external entity

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/1d29289a-6fec-4cd7-8f4c-a313a932df43)

- We insert the payload copied from the Burp Collaborator

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/c8200b1b-7095-4af3-ae91-33a9e2329a2e)

- We see some DNS and HTTP interactions that were initiated by the application as the result of our payload. Thus the lab gets solved.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/68af19d5-0282-4370-b33d-544f5dfbe8cf)

