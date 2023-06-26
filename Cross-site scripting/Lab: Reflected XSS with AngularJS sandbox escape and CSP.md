- Consider a shopping appllication that uses Content security policy and AngularJS.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/04ca42d4-c18f-4a51-9f40-307a5ee1bdf8)

- We perform a cross-site scripting attack that bypasses CSP, escapes the AngularJS sandbox, and alerts document.cookie. We go to the exploit server to perform this.

  ![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/fad7fedb-d184-4de3-b4cd-65942a588c57)

- Now we paste inject the script tag with a URL 'https://YOUR-LAB-ID.web-security-academy.net/?search=%3Cinput%20id=x%20ng-focus=$event.composedPath()|orderBy:%27(z=alert)(document.cookie)%27%3E#x'

 ![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/2158322e-cd84-4ff7-9738-7c47519a736b)

- The exploit uses the ng-focus event in AngularJS to create a focus event that bypasses CSP. It also uses $event, which is an AngularJS variable that references the event object. The last element in the array contains the window object.WHen we deliver our exploit to the victim, our lab gets solved.

  ![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/203100c3-8a07-4cdb-a804-8f53a24a5ad9)


 

  
