# CypressTests
# Web Application Login Functionality Automation

This repository contains automated tests for a web application's login functionality using both Cypress and Selenium. The tests cover scenarios such as successful login, failed login, and error message display when login fails. The automation is integrated into a CI/CD pipeline using GitHub Actions.

## Table of Contents

- [Test Scenarios](#test-scenarios)
- [Technologies Used](#technologies-used)
- [Cypress Setup](#cypress-setup)
- [GitHub Actions CI/CD](#github-actions-cicd)
- [Running Tests Locally](#running-tests-locally)

## Test Scenarios

The login functionality is tested for the following scenarios:

1. **Successful login with valid credentials.**
2. **Failed login with invalid credentials.**
3. **Error message display when login fails.**

## Technologies Used

- **Cypress**: A modern end-to-end testing framework.
- **Selenium**: A widely used tool for automating web browsers.
- **GitHub Actions**: CI/CD pipelines for automating test runs on each code push.

## Cypress Setup

### Prerequisites

1. **Node.js**: Ensure you have Node.js installed on your machine.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
2. Install the dependencies:
npm install
3. Running Cypress Tests Locally
   You can run the Cypress tests using the following command:
   npx cypress open
4. To run the tests in headless mode:
    npx cypress run

