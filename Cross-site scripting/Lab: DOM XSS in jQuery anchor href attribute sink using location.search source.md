- Consider a shopping application that contains a DOM-based cross-site scripting vulnerability in the submit feedback page.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/2ab503b2-0e15-4b61-9b96-37a36c6ae191)

- It uses the jQuery library's $ selector function to find an anchor element, and changes its href attribute using data from location.search.
- 
