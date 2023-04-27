**OBJECTIVE**
 
Having already determined the number of required columns, you can probe each column to test whether it can hold string data by submitting a series of UNION SELECT payloads that place a string value into each column in turn
- UNION SELECT 'a',NULL,NULL,NULL--
- UNION SELECT NULL,'a',NULL,NULL--
- UNION SELECT NULL,NULL,'a',NULL--
- UNION SELECT NULL,NULL,NULL,'a'--

If the data type of a column is not compatible with string data, the injected query will cause a database error.

Conversion failed when converting the varchar value 'a' to data type int.

If an error does not occur, and the application's response contains some additional content including the injected string value, then the relevant column is suitable for retrieving string data. 
