- Consider a shopping application that contains a stored cross-site scripting vulnerability in the comment functionality.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/6bddd128-c06f-429a-beba-76961df11c0d)

- We are going to submit a comment that calls the alert function when the comment author name is clicked. Now leave a comment in the comment section.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/a2fa0d16-a408-4984-a877-34bc2aef0dbf)

- Now capture it using BurpSuite

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/b4fdfb23-8a04-4a96-a81b-7d946cfc2d42)

- Now we replace our input with the following payload to inject a JavaScript URL that calls alert.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/613333c7-31e5-4f2a-a027-00f3c3eeea34)

- This makes the lab solved.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/e6d9a393-5898-4958-86c6-e10b5fd0099b)
