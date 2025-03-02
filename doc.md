# API -testing
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




![alt text](../../../../Pictures/api-testing-touchscreen-postman-illustration.svg)


