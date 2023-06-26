- Consider a shopping application that has a stock check feature which fetches data from an internal system.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/c2303df7-08d5-483a-ab0f-6542385323f1)

- Now when we get into '/admin' platform we are not authorized.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/79f24149-4340-465a-b425-bcfe2282b5a7)

- Now we get into 'check stock' and capture it using BurpSuite.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/7278bf2d-f257-4491-b6cd-9ded8f164109)

- Now we use the stockapi syntax to exploit the vulnerability and delete the username carlos.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/2dfd0852-314a-47dc-a999-c90eecf92ed9)

- Thus the username carlos gets deleted and lab gets solved.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/dc20fcd5-f365-495e-b809-d67ad02467da)

