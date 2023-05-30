- Consider a shopping application with a SQL injection vulnerability.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/d97d3547-ccf1-48b8-a0b5-0a2dd2ab68bb)

- We append a single quote to the value of your TrackingId cookie and send the request which results in a error.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/2b7d5652-c60d-4d1c-aff1-1ad5f49cdfb4)

- Now in the query we add comment characters to check whether the query syntax is correct or not. 

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/051b2101-03e9-4aab-a8fe-1e4d4885b76f)

- Now we add a SELECT subquery with int characters to get a different error saying that an AND condition must be a boolean expression.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/e4949098-0660-4caa-b555-a0b6af7006c9)

- Just adding a comparator '=' to the query will result in the query syntax being correct.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/167ff356-c3b2-4066-8ff2-6ff8c29411e9)

- Now we try to retrieve the username from the users table by generating an error 

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/ce9fed72-9af2-4a4e-b3da-2d9843d03d95)

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/06578422-5019-4c3c-a2f3-a81972e72bf0)

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/a39a2d5b-2421-4f93-92ee-ed014736dafd)

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/f263c299-21bd-45c4-8dc6-efd16bb87a2e)

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/42659c9a-0385-479f-b403-b0e144cdf10d)


