# OpenCart

Welcome to the <b>OpenCart Manual Testing</b> repository. This project focuses on the manual testing efforts for the OpenCart e-commerce platform using tools such as <b>TestRail</b> for test case management and <b>JIRA</b> for issue tracking. The objective is to ensure the stability, functionality, and usability of the OpenCart platform through well-documented test plans, detailed test cases, and organized bug reporting.

<br>

## Table of Contents
1. Project Overview
2. Testing Scope
3. Tools Used
4. Test Plan
5. Test Execution
6. Defect Management
7. Contributing


<br> 


## Project Overview
<b>OpenCart</b> is a popular open-source e-commerce platform that allows users to create and manage online stores. The goal of this project is to perform comprehensive Manual Testing to ensure that the platform's functionalities meet the required specifications, are bug-free, and provide a smooth user experience.

This project focuses on testing different aspects of the OpenCart platform, including but not limited to:

- User interface (UI) testing
- Functional testing
- Regression testing
- Cross-browser testing
- Responsive design testing

<br>

## Testing Scope
The primary scope of this project includes the following modules of the OpenCart platform:

1. <b>User Management:</b> Registration, login, password recovery, user roles.
2. <b>Product Management:</b> Adding, editing, and deleting products, categories, and inventory management.
3. <b>Cart and Checkout Process:</b> Cart functionality, payment gateways, order processing, confirmation emails.
4. <b>Admin Panel:</b> Managing store settings, user permissions, product categories, sales reports, and data analysis.
5. <b>Shipping and Tax Settings:</b> Testing different shipping methods and tax rules.
6. <b>Promotions and Discounts:</b> Coupon codes, special offers, and discount rule management.
7. <b>Reports:</b> Sales, product views, and customer activity reports.


<br>


## Tools Used
We use the following tools to facilitate our manual testing process:

- <b>TestRail:</b> For test case management and tracking. All test cases, test plans, and results are documented in TestRail.
- <b>JIRA:</b> For issue tracking and defect management. Bugs and feature requests are logged and tracked using JIRA.


<br>


## Test Plan
The testing strategy for this project follows a structured approach to ensure complete coverage of all critical functionalities of the OpenCart platform.


### Test Case Creation
- Test cases are written and managed in TestRail.
- Test cases cover all modules mentioned in the testing scope.
- Each test case includes:<br>
  - Test ID
  - Test Objective
  - Preconditions
  - Steps to Execute
  - Expected Result

### Test Types
The following types of testing will be performed:

1. <b>Functional Testing:</b> Verifying that each feature works according to the requirements.
2. <b>Regression Testing:</b> Ensuring that existing functionalities work after code changes.
3. <b>Cross-Browser Testing:</b> Testing across multiple browsers (e.g., Chrome, Firefox, Safari).
4. <b>Responsive Testing:</b> Testing across different screen sizes and devices.


<br>


## Test Execution
### Running Test Cases
1. Navigate to the TestRail project for OpenCart.
2. Select the relevant Test Plan or Test Suite.
3. Execute the test cases by following the steps outlined in each test case.
4. Mark the result for each test case:
    - <b>Pass:</b> The functionality behaves as expected.
    - <b>Fail:</b> The functionality does not behave as expected.
    - <b>Blocked:</b> Testing cannot proceed due to an external dependency.
    - <b>Skipped:</b> Test case is not applicable for this cycle.

### Test Reports
Upon completion of each testing cycle, a report is generated in TestRail summarizing:

- Total test cases executed
- Pass percentage
- Failures and blocked test cases
- Coverage status


<br>


## Defect Management

### Reporting Bugs
Defects identified during testing are logged in JIRA with the following details:

- <b>Issue Type:</b> Bug
- <b>Priority:</b> Blocker, Critical, Major, Minor, Trivial
- <b>Description:</b> Clear description of the issue.
- <b>Steps to Reproduce:</b> Detailed steps to recreate the issue.
- <b>Expected Result:</b> What should happen.
- <b>Actual Result:</b> What actually happened.
- <b>Attachments:</b> Screenshots, videos, logs if necessary.

### Issue Tracking
- Once a bug is logged in <b>JIRA</b>, it is assigned to the relevant developer.
- The bug's status is updated throughout its lifecycle (e.g., <b>Open</b>, <b>In Progress</b>, <b>Resolved</b>, <b>Closed</b>).
- All resolved bugs are verified during regression testing before being marked as <b>Closed</b>.


<br>


## Contributing
We welcome contributions from the community to improve our testing efforts! If you'd like to contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Write or update test cases in <b>TestRail</b>.
4. Log any bugs found in <b>JIRA</b>.
5. Submit a pull request with a detailed description of the changes.

<br>

Please ensure that all contributions align with our testing standards and guidelines.
