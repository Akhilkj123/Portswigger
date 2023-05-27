## OS Command Injection 
It is a web security vulnerability that allows an attacker to execute arbitrary operating system (OS) commands on the server that is running an application, and typically fully compromise the application and all its data.

### Executing arbitrary commands
For historical reasons, the functionality is implemented by calling out to a 
- **shell command** with the product and store IDs as arguments:
- **stockreport.pl** 381 29
 
 This command outputs the stock status for the specified item, which is returned to the user.

Since the application implements no defenses against OS command injection, an attacker can submit the following input to execute an arbitrary command:
& echo aiwefwlguh &
