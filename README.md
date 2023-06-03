# Random-User-API-Performance-Test
**Scenario: Find out the actual TPS for if 120000 users can give load for 12 hours Perform load test on this URL: https://random-data-api.com/api/v2/users**
## Technology used: Apache JMeter

 **I used it for these characteristics:** 

  - **Open source application** – Apache JMeter is an openly available free tool & it facilitates users or developers to use the code for other development or modification purpose.
  - **Platform independent** – It can run on any platform & also it is capable enough to check the load & performance of any server requests.
  - **User friendly GUI** – Its user-friendly, simple & easy to understand.
  - **Installation** – It’s easy to install on different OS. 
  - **Record & Run**: JMeter provides the facility to record the steps by using Blaze master add-on & run with any number of threads & listeners.

## Server URL:

- Perform load test on this URL.
- Link: https://random-data-api.com/api/v2/users

## Jmeter Performance Testing Image
- I have done performance testing including **Load Testing** and **Stress Testing**.
- **Load Testing:** This testing is used to check the extreme load of a system that can be aimed to handle. 
  I started with 834 requests in 300 seconds and finally I executed with 4167 requests in 1500 seconds. I got the expected TPS (2.7) for every test iteration.
 
![Screenshot 2023-06-03 112705](https://github.com/mahmudulkhan900/Random-User-API-Performance-Test/assets/60164456/e05bdc41-d375-4969-9d5b-6000e9470b17)

- **Stress Test:**  This test tries to break the system by crushing its resources. I checked it in 25 minutes (1500 seconds) considreing 4167, 4500, 4700, 5000 requests. This server successfully run with these requests except 5000 requests in 1500 seconds. It shows an error 1% that is called as bottleneck point.
- 
  ![Screenshot 2023-06-03 113039](https://github.com/mahmudulkhan900/Random-User-API-Performance-Test/assets/60164456/61d2e8c5-9945-45c0-9efb-6322c0d01a2c)
  
- Random-User-API-Performance-Test Image Drive link:  https://docs.google.com/spreadsheets/d/1orV8-Bxr5iOpCbNwQrXtwbDN0byd0o0GTE_zdSPea2s/edit?usp=sharing
