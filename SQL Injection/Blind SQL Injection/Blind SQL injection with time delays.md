
- We now take a vulnerable webpage

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/549fee43-8f08-4f48-ace1-40378760d299)

- This application uses a tracking cookie for analytics, and performs a SQL query containing the value of the submitted cookie. 
- So now, we submit a query in TrackingId to make the page a delay of 10 sec

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/c94b60c5-ad3e-48ef-81d6-b2311a2345be)

- Since the query is executed synchronously, it is possible to trigger conditional time delays to infer information.

- The result is as shown

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/075b4bdc-38a9-48ac-95f1-95337327a629)

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/8df03380-e5ea-45f7-9d9d-076b96be1232)



