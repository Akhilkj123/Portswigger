
## Directory Traversal
- It is a web security vulnerability that allows an attacker to access arbitrary files on a server that is currently running an application. The attacker may get access to the code of the application, any data content in it or even any sensitive information. The attacker may even get to edit the arbitrary files which can result in change of the entire application.

### Reading arbitrary files via directory traversal
- The image files in a shopping application gets saved in /var/www/images of a server. The attackers intention is to read arbitrary files of the server. The attacker edits the filename in the server to be a location where the arbitrary files are present(for eg. /etc/passwd).

