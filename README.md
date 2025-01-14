# Test Automation Project

## Overview
This project is designed to automate both UI and API testing for our application. It uses Selenium for UI automation and RestAssured for API automation, along Maven for test management and execution.

## Features
- Automated UI testing, Test case for search bar retrieves accurate product results or not.
- Automated UI testing, Test case for cart functionality operates correctly or not.
- Build and dependency management with Maven
- src/main/java: Contains the main application code
- src/test/java: Contains the test cases
- pom.xml: Maven configuration file

## Why This Framework?

### Versatility
This framework supports both UI and API automation, making it a comprehensive solution for end-to-end testing. By using Selenium for UI tests and RestAssured for API tests, we can ensure that both the front-end and back-end of our application are thoroughly tested.

### Scalability
With the integration of Maven, the framework is highly scalable. Maven handles build and dependency management, making it easy to add new tests and manage dependencies as the project grows.

### Ease of Use
The framework is designed to be user-friendly, with clear project structure and detailed documentation. This makes it easy for new team members to get up to speed quickly and contribute to the project.

### Community Support
Selenium, RestAssured, JUnit, and Maven are widely used and have strong community support. This means that any issues or questions can be quickly resolved with the help of extensive documentation and community forums.

### Continuous Integration
The framework is compatible with continuous integration tools like Jenkins, allowing for automated test execution and reporting. This helps in maintaining the quality of the application by catching issues early in the development process.

## Prerequisites
- Java 11 or higher
- Maven 3.6.3 or higher

## Installation
1. Clone the repository:
    ```bash
    git clone git clone https://github.com/abu-shaleh/Testwsd.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Testwsd
    ```
3. Install dependencies:
    ```bash
    mvn install
    ```

## Running Tests
To run the tests, use the following command:
```bash
mvn test


