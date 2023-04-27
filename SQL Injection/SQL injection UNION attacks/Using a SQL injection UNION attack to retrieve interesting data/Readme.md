**OBJECTIVE**

- When we have determined the number of columns returned by the original query and found which columns can hold string data, we are in a position to retrieve interesting data.

- Suppose original query returns two columns, both of which can hold string data and database contains a table called users with the columns username and password then the following query can be submitted:

' UNION SELECT username, password FROM users--

 - The crucial information needed to perform this attack is that there is a table called users with two columns called username and password.

