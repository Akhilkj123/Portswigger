When performing a SQL injection UNION attack, there are two effective methods to determine how many columns are being returned from the original query. 

1st method
- Injecting a series of ORDER BY clauses and incrementing the specified column index until an error occurs.

Example:

 ORDER BY 1--
 
 ORDER BY 2--
 
 ORDER BY 3--
 
 This series of payloads modifies the original query to order the results by different columns in the result set.
 
 When the specified column index exceeds the number of actual columns in the result set, the database returns an error.
 
 2nd method
 
 - It involves submitting a series of UNION SELECT payloads specifying a different number of null values: 
 
UNION SELECT NULL--

UNION SELECT NULL,NULL--

UNION SELECT NULL,NULL,NULL--

If the number of nulls does not match the number of columns, the database returns an error.
