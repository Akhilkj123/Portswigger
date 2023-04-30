
We perform SQL Injection UNION attack to query the dtatabase type and version. This is a webpage which is vulnerable to SQL Injection attack.

![image](https://user-images.githubusercontent.com/65653010/235273351-fa77f381-7765-42b1-a799-c982a5f20eeb.png)

We give a query:
UNION SELECT 'abc' 'def' FROM dual-- 

This is given to verify that the query is returning two columns, both of which contain text, using a payload 'abc 'def'.

![image](https://user-images.githubusercontent.com/65653010/235273301-b93eae39-95b4-419b-8803-4aed48fd1342.png)

![image](https://user-images.githubusercontent.com/65653010/235273502-1726ab10-c168-4d7f-8f5c-52a1b498ff9a.png)
