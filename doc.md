# API -testing

![image](https://github.com/user-attachments/assets/a7149d80-ca82-46a6-8e2d-37cf256e58d0)


API testing can help teams confirm that their API's endpoints, methods, and integrations are functioning as expected.

API (Application Programming Interface) testing is a type of software testing that involves testing APIs directly and as part of integration testing to determine whether they meet expectations for functionality, reliability, performance, and security. Unlike UI testing, API testing focuses on the business logic layer of the software architecture.

## Key Aspects of API Testing:
Functionality: Ensuring the API works as expected.

Reliability: Ensuring the API can be consistently connected to and deliver consistent results.

Performance: Ensuring the API performs well under load.

Security: Ensuring the API is secure from external threats.


## How to Do API Testing Using Postman

Postman is a popular tool for API testing that allows you to create, share, test, and document APIs.
You can download postman API using following link:
```
https://www.postman.com/downloads/
```

You can check postman already exists or not:
```
postman --version
```

This is the overview of the postman API :
![Screenshot from 2025-03-02 23-31-45](https://github.com/user-attachments/assets/336b528f-0803-4d17-8923-4ee312e16974)



Here’s a step-by-step guide on how to perform API testing using Postman:

1. Install Postman
2. Create a New Request

   - Open Postman.
   - Click on the "New" button and select "Request".
   - Name your request and optionally save it to a collection.

3. Set Up the Request

   - Select the HTTP Method: Choose the appropriate HTTP method (GET, POST, PUT, DELETE, etc.) from the dropdown menu.
   - Enter the URL: Input the API endpoint URL.
   - Add Parameters: If the API requires query parameters, you can add them in the "Params" tab.
   - Add Headers: If the API requires headers, you can add them in the "Headers" tab.
   - Add Body: For methods like POST or PUT, you may need to send a request body. You can add this in the "Body" tab, 
     selecting the appropriate format (e.g., JSON, form-data).
     
4. Send the Request

   - Click the "Send" button to send the request to the API.
   - The response will be displayed in the lower section of the Postman window, including the status code, response time, and 
     the response body.

5. Validate the Response

   - Status Code: Check if the status code is as expected (e.g., 200 for success, 404 for not found).
   - Response Body: Verify that the response body contains the expected data.
   - Headers: Check if the response headers are as expected.


## Example: Testing a GET Request

   - Method: GET
   - URL: https://api.example.com/users
   - Headers: Authorization: Bearer <token>


## development level of testing

   ![image](https://github.com/user-attachments/assets/8c14f408-aeaa-4ee5-a3df-691b25c22c5d)

## API testing types

 - Unit testing
 - Load testing
 - End-to-end testing
 - Contract testing

![image](https://github.com/user-attachments/assets/55ca8386-3efd-4b93-a8a0-ca87d3a4db10)

<br>

## contract testing

An API contract is a human- and machine-readable representation of an API's intended functionality. It establishes a single source of truth for what each request and response should look like—and forms the basis of service-level agreements (SLAs) between producers and consumers. API contract testing helps ensure that new releases don't violate the contract by checking the content and format of requests and responses.

## unit testing

API unit testing is the process of confirming that a single endpoint returns the correct response to a given request. Unit tests may validate that an endpoint handles optional parameters correctly, or that it returns the appropriate error message when sent an invalid request.

## End-to-end testing

Whereas unit tests help developers ensure that individual endpoints are working as expected, end-to-end tests are used to validate key user journeys that may involve multiple endpoints and APIs. End-to-end API testing involves chaining requests together and confirming that each one is working properly, which helps teams surface issues in complex workflows before users do.

## Load testing

API load testing enables developers to confirm whether their API is able to operate reliably during times of peak traffic. It typically involves using a testing tool to simulate large request volumes and measure the resulting response times and error rates. This type of testing is often performed in anticipation of a significant load increase, such as right before a product launch or yearly sale.

## Security testing

API security testing involves identifying and resolving security vulnerabilities within APIs. This type of testing is designed to discover any potential weaknesses that may result in unauthorized access, data breaches, injection attacks, or other security risks.

## Integration testing

API integration testing is a critical step in ensuring that different parts of a system are compatible with one another. It helps confirm that APIs can reliably and efficiently communicate and transfer data between one another—even as they evolve over time.

## Functional testing

API functional testing verifies that an API meets its specified requirements. This type of testing involves sending specific requests to the API, analyzing the responses, and comparing the actual outcomes with the expected results to ensure the API performs as designed.



## What are some common bugs found in API testing?

The API testing process can surface a wide range of bugs and issues. Some of the most common ones include:

   - Incorrect data formatting: API tests can help uncover responses that return data in the wrong format, such as JSON 
     instead of XML, or vice versa. This can cause parsing errors in the client application.
     
   - Missing data or parameters: API testing can reveal problems with API authentication or authorization, such as incorrect 
     handling of API keys, tokens, or permissions, resulting in unauthorized access or denial of service.
     
   - Performance and scalability problems: API load testing can determine whether an API can perform well under load and 
     scale appropriately. Issues with performance and scalability can lead to slow response times, timeouts, or service 
     disruptions.
     
   - Concurrency issues: API testing can surface race conditions or threading issues in the API implementation, which can 
     lead to unpredictable behavior or data corruption.
     
   - Security vulnerabilities: API security tests can reveal security flaws, such as lack of encryption, exposed sensitive 
     information, or insufficient rate limiting. They can also catch improper validation of input data, which can lead to SQL 
     injection or cross-site scripting (XSS).
     
   - Compatibility issues: API testing can detect when updates in a new API version cause compatibility issues with existing 
     client applications, leading to broken functionality.
     
   - Integration problems: API integration tests help teams uncover instances in which APIs fail to integrate correctly with 
     other systems or services, resulting in data inconsistencies or interoperability issues.
     
   - Cross-Origin Resource Sharing (CORS) misconfigurations: API tests help surface improper CORS configuration, which can 
     cause cross-origin requests to fail and result in client-side issues.


## What are the benefits of API testing?

API testing plays a crucial role in modern software development workflows, and its benefits cannot be overstated. These benefits include:

   - Quality assuarance
   - Early issue detection and resolution
   - Resource conservation
   - Rapid interaction


## What are some API testing best practices?

There are several best practices that teams should follow to implement an API testing strategy that is efficient and sustainable. These best practices are:  

   - Create a dedicated testing environment
   - Automate your API tests
   - Run tests throughout the API lifecycle
   - Write reusable subtests
   - Keep your tests organized


### Automate your API tests

While manual API testing can help developers debug specific problems, test automation enables teams to systematize their approach in order to ensure consistent coverage and reduce the possibility of human error. Teams can use a variety of tools to create test suites and schedule executions to occur at specific times, at specific frequencies, or in CI/CD pipelines after every commit or push.
     


![alt text](../../../../Pictures/api-testing-touchscreen-postman-illustration.svg)


