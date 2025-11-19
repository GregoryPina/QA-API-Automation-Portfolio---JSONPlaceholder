# API Automation Portfolio

I built this project to demonstrate a robust automated testing strategy for REST APIs. Using Postman and JavaScript, I created a collection that validates the full CRUD lifecycle of the JSONPlaceholder API.

My goal here was not just to check for "200 OK", but to ensure data consistency and reliability through automated assertions.

## Key Features
Instead of simple static tests, I implemented:
* **Dynamic Variables:** Using Environment Variables ({{baseURL}}) to make the suite adaptable.
* **Chained Requests:** Validating that data created in a POST request persists correctly in subsequent GET/PUT calls.
* **Clean Assertions:** Using pm.expect and JavaScript logic to validate JSON schemas and specific data fields (not just text search).
* **Negative Testing:** Handling empty responses (DELETE) and verifying correct status codes (201 vs 200).

## Stack
* **Postman** (Collection & Runner)
* **JavaScript** (Test Scripts)
* **Newman** (Ready for CI/CD integration)

## How to Run
1. Download the .json files from this repo.
2. Import the Collection and Environment into Postman.
3. Select the "ReqRes - QA" environment.
4. Hit Run in the Collection Runner to see the results.

---
Created by Gregory Oliveira Pina - QA Specialist
