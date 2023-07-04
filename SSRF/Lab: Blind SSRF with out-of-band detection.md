- Consider a shopping application that uses analytics software which fetches the URL specified in the Referer header when a product page is loaded.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/643c6582-e39a-4344-8b1e-51faddb3b967)

- We use this functionality to cause an HTTP request to the public Burp Collaborator server. now we capture the traffic using BurpSuite

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/54c05b09-1767-401c-a7e1-e6e595eea790)

- Now we insert a Burp collaborator payload into it ad forward it.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/c86a7223-b818-4b2c-9f3c-96ba5355a34f)

- When we visit the Burp collaborator we see the HTTP and DNS request present and the lab gets solved.

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/70c312bf-42f9-48e3-a94a-98d3e05aef35)

![image](https://github.com/Akhilkj123/Portswigger/assets/65653010/dc2266a2-f923-4d41-a42b-f5f39aa002a5)



