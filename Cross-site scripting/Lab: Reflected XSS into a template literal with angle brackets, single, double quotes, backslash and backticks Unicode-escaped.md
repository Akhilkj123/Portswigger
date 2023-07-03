- Consider a shopping application that contains a reflected cross-site scripting vulnerability in the search blog functionality.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/be8be325-3177-418a-97eb-027abe2194d8)

- The reflection occurs inside a template string with angle brackets, single, and double quotes HTML encoded, and backticks escaped. We perform a cross-site scripting attack that calls the alert function inside the template string.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/2b53a192-e7b2-4a3f-86f9-691655d1b7bf)

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/aa391254-8b95-4994-9079-cdb9e15b88e6)

- Now we replace our input with the following payload to execute JavaScript inside the template string

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/0f9864d1-b23b-448d-913e-5efc9d1084ad)

- This now results in a alert bix and the lab gets solved.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/fdb21ba4-d5a6-4756-912d-b29e51c5b608)

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/f8af5b71-cd87-4881-8df1-5103a0badf1a)

