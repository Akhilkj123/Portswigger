- Consider a shopping application which contains an OS command injection vulnerability in the product stock checker. 

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/41ec5d36-bfde-4154-a381-c1b75fabdd8e)

- The application executes a shell command containing user-supplied product and store IDs, and returns the raw output from the command in its response.
- Now we are going to add commands in the storeID of the application

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/35371b87-7387-45dd-8f2d-9e17b7820156)

- Both the commands get executed and it shows the whoami

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/3d310a58-48fe-40ea-8030-bd8884e89435)

- Then it gets the lab solved.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/9abf68bc-c183-4fd9-813c-67cb7b387ff6)
