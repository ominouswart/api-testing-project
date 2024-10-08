# Postman API Tests

## 0. What are we testing and what is this about

This repository contains a suite of Postman tests designed to validate the functionality of https://www.automationexercise.com/. The tests check various endpoints to ensure they behave as expected, including checking response status codes, data integrity.

## 1. Requirements

To run the tests in this repository, you will need:

- **Node.js** (version 16.x or later)
- **Newman** (command-line tool for running Postman collections)
- **Postman** (for creating and modifying collections)(optional)

## 2. How to install

Follow these steps to set up your environment:

1. **Clone the repository**:
   ```
   git clone https://github.com/ominouswart/api-testing-project.git
   cd api-testing-project
   ```
2. **Install project dependencies**:
   ```
   npm install
   ```

## 3. How to run tests

 You can run the Postman tests locally using the following command:

   ```
   newman run ./postman-tests/Postman-project.postman_collection.json
   ```

## 4. Any issues with tests or website

 Some tests require you to use 'form-data', while others only work with a query string.