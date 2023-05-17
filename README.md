# Newman Project for Petstore-Swagger API Automation

This project provides API automation tests for the Petstore-Swagger API using Newman CLI. It includes a Postman collection (`PET-Store-Swagger.postman_collection.json`) and a script to run the tests and generate an HTML report.

## Requirements

To run this project, ensure you have the following dependencies installed:

- Newman: ^5.3.2
- Newman Reporter HTML: ^1.0.5

You can install these dependencies by running the following command:

```
npm install
```

## How to Run

To execute the API automation tests, use the following script:

```
npm run test
```

The script internally uses the `newman run` command to run the tests. It specifies the Postman collection file (`PET-Store-Swagger.postman_collection.json`) and an environment variable (`BASE_URL`) that sets the base URL for the API. The tests are executed using the Newman CLI, and the resulting report is generated in HTML format.

## HTML Report

After running the tests, you can find the HTML report in the `newman/` directory. Open the HTML file in your web browser to view the detailed test results, including the request/response details, assertions, and overall test statistics.