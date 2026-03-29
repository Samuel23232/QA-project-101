# QA-project-101
 (E-Commerce)
 
# Project Overview

I tested the public REST API provided by DummyJSON, which simulates a real-world backend for an e-commerce application.
The API provides endpoints for resources such as login,product,carts, recipes, and users, post, comments, todos and quotes returning JSON responses similar to what a production backend would return.

----  Why it was tested:
  
As a Quality Assurance in training, I needed a realistic API environment to practice:
- Writing API test cases
- Validating HTTP status codes
- Verifying JSON response structures
- Performing positive and negative testing
- Running automated API tests using Postman and Newman
DummyJSON provides stable, predictable endpoints that make it ideal for learning how backend systems are tested in real projects

--- The Goal of Testing

- The goal of this testing project was to simulate how a QA engineer would test the backend of an e-commerce system by:
- Ensuring endpoints return correct data
- Verifying the API handles invalid inputs properly
- Confirming response time and reliability
- Documenting test cases, bugs, and test evidence
- Creating a reusable Postman collection that can be run with Newman

---- Tools Used
- Postman
- Newman
- Google Sheets (Test Cases)
- DummyJSON API
- GitHub

--- Testing Scope:

- Authentication endpoints
- Product endpoints
- Cart endpoints
- Recipe endpoints
- User endpoints
- Post endpoint
- Comments endpoint
- Todos endpoint
- Quotes endpoint
- Status code validation
- Response body validation
- Negative testing

## ▶️ How to Run the Tests

Step-by-step so anybody can run it.

1. Import the Postman collection.
2. import the New Environment.postman_environment
3. Set base URL to: https://dummyjson.com
4. Run the collection
5. Or run using Newman:
