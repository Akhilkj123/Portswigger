- Consider a shopping application that uses AngularJS in an unusual way where the $eval function is not available and you will be unable to use any strings in AngularJS.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/4ed46f81-556c-4818-a8c4-c101b030d366)

- We perform a cross-site scripting attack that escapes the sandbox and executes the alert function without using the $eval function. We inject a URL 'https://YOUR-LAB-ID.web-security-academy.net/?search=1&toString().constructor.prototype.charAt%3d[].join;[1]|orderBy:toString().constructor.fromCharCode(120,61,97,108,101,114,116,40,49,41)=1' to the page, which returns an alert box as result.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/7e53edf1-d53a-4eb6-9dbd-a837f98ba18f)

- The exploit uses toString() to create a string without using quotes. we use the fromCharCode method generate our payload by converting character codes into the string x=alert(1). Because the charAt function has been overwritten, AngularJS will allow this code where normally it would not.Thus the lab gets solved.

 ![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/b0af5f7c-4291-4055-ac0a-2d92638ea454)

  
 
