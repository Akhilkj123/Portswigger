- Consider a shopping application vulnerable due to a logic flaw in its password brute-force protection. We can reset the counter for the number of failed login attempts by logging in to your own account before this limit is reached.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/33f99ca2-a231-4d94-9ca3-7cfb2703cebe)

- Now enter invalid credentials to it

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/925ac849-011d-4ce9-8258-388bab131ec8)

- Now capture it using Burpsuite and will se the n number of attempts performed 

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/e031b3b5-1271-41a2-bb30-eb6e1e725ece)

- Now if we enter legitimate username and password we get

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/b51a23d0-6f1c-4735-ba56-679d92eb4856)

- Now sent the request to the intruder and give the payload for username and password

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/fcb1f383-5d9f-47ab-8ac6-44a7fb28f081)

- Now if we start the attack the correct credentials shows 302 status 


![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/a21a055b-f3fe-4993-8e20-83473048a541)

-Thus the lab gets solved

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/a4f928d9-9a1d-49d2-bf70-02723cd64af1)


