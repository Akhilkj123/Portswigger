**OBJECTIVE**
- We can easily retrieve multiple values together within this single column by concatenating the values together, ideally including a suitable separator to let you distinguish the combined values. 
- We can perform this the following query:

    ' UNION SELECT username || '~' || password FROM users--
- This uses the double-pipe sequence || which is a string concatenation operator.
- The injected query concatenates together the values of the username and password fields, separated by the ~ character. 
- The results from the query will let you read all of the usernames and passwords.
