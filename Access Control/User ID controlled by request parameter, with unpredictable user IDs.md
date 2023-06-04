- Consider a shopping application which has a horizontal privilege escalation vulnerability on the user account page, but identifies users with GUIDs.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/ea6c0be1-b2f4-4ae6-adf5-fa969a2b5da1)

- Now we find a post given by carlos and find his user ID

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/74792d1d-9344-4ccb-9116-d7c04e8c2a31)

- Now login as wiener with credentials provided 

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/78d67c1c-804e-46a9-828f-2b299c944e27)

- Now capture the my account page using Burpsuite

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/14ed0e2d-f6c4-4c82-a0ae-7d618d20a3c0)

- Now replace the userID of carlos with wiener to recevie the API key of the former

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/b30ae9d8-0eb6-467e-8f89-05a4e08a242a)

- By submiting the API the lab gets solved

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/dffe76a8-9c2a-4936-be63-ed4ae1ba5de6)

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/e97d6cb1-af0b-4407-90b0-45b01900b03b)

