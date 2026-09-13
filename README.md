# End-to-End QA Testing : UI Manual Testing & REST API Automation

## Project Overview
Welcome to my QA Testing project! This repository contains a complete End-to-End Quality Assurance (QA) testing suite demonstrating both UI Manual Testing on an E-Commerce application and Automated Backend REST API Testing using Postman.

---

## Part 1: UI Manual Testing & Jira Defect Tracking

- **Application Tested:** SauceDemo E-Commerce Website (https://www.saucedemo.com/)
- **Manual Test Cases:** Designed and executed detailed manual test cases for User Login, Product Search, Shopping Cart management, and Checkout processes.
- **Defect Tracking (Jira):** Reported UI and functional bugs and managed complete issue lifecycles using Jira.
- **Artifacts Location:** Check the `Manual-Testing` folder in this repository for the Excel test suite and Jira proof.

---

## Part 2: Automated REST API Testing (Postman)

- **Target API:** JSONPlaceholder Mock REST API (https://jsonplaceholder.typicode.com/)
- **CRUD Operations Automated:**
  - `GET /users`: Fetched user list and verified `200 OK` status code.
  - `POST /users`: Created a new user entity and verified `201 Created` status code.
  - `PUT /users/1`: Updated existing user details and verified `200 OK` status code.
  - `DELETE /users/1`: Deleted user record and verified `200 OK` status code.
- **Negative Boundary Testing:**
  - `GET /users/9999`: Tested a non-existing user ID to verify `404 Not Found` response handling.
- **Environment Management:** Used Postman environment variables (`{{baseUrl}}`) for dynamic URL handling.

---

## Author
- Quality Assurance & API Testing Portfolio
- Designed and executed to demonstrate hands-on QA methodology in Manual UI Testing, Bug Tracking, and API Automation.
