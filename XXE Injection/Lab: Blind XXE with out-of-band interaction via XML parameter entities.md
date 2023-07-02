- Consider a shopping application that has a "Check stock" feature that parses XML input, but does not display any unexpected values, and blocks requests containing regular external entities.

 ![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/ccd0644a-a58f-49a2-862c-b2a9ab092076)

- We use a parameter entity to make the XML parser issue a DNS lookup and HTTP request to Burp Collaborator. We insert the following external entity definition in between the XML declaration and the stockCheck element.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/3f69e51e-665b-4e22-89c4-c59b38a54aeb)

- We will see some DNS and HTTP interactions that were initiated by the application as the result of our payload.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/21f976cf-33f8-4a28-883a-4914a1398989)

- Thus the lab gets solved.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/1533c162-81cc-4112-b966-88ce4469ce68)
