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
8. License


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

1. <b>User Management</b>: Registration, login, password recovery, user roles.
2. <b>Product Management</b>: Adding, editing, and deleting products, categories, and inventory management.
3. <b>Cart and Checkout Process</b>: Cart functionality, payment gateways, order processing, confirmation emails.
4. <b>Admin Panel</b>: Managing store settings, user permissions, product categories, sales reports, and data analysis.
5. <b>Shipping and Tax Settings</b>: Testing different shipping methods and tax rules.
6. <b>Promotions and Discounts</b>: Coupon codes, special offers, and discount rule management.
7. <b>Reports</b>: Sales, product views, and customer activity reports.


<br>


## Tools Used
We use the following tools to facilitate our manual testing process:

TestRail: For test case management and tracking. All test cases, test plans, and results are documented in TestRail.
JIRA: For issue tracking and defect management. Bugs and feature requests are logged and tracked using JIRA.


<br>


## Test Plan
The testing strategy for this project follows a structured approach to ensure complete coverage of all critical functionalities of the OpenCart platform.


### Test Case Creation
Test cases are written and managed in TestRail.
Test cases cover all modules mentioned in the testing scope.
Each test case includes:
Test ID
Test Objective
Preconditions
Steps to Execute
Expected Result

### Test Types
The following types of testing will be performed:

Functional Testing: Verifying that each feature works according to the requirements.
Regression Testing: Ensuring that existing functionalities work after code changes.
Cross-Browser Testing: Testing across multiple browsers (e.g., Chrome, Firefox, Safari).
Responsive Testing: Testing across different screen sizes and devices.


<br>


## Test Execution
### Running Test Cases
Navigate to the TestRail project for OpenCart.
Select the relevant Test Plan or Test Suite.
Execute the test cases by following the steps outlined in each test case.
Mark the result for each test case:
Pass: The functionality behaves as expected.
Fail: The functionality does not behave as expected.
Blocked: Testing cannot proceed due to an external dependency.
Skipped: Test case is not applicable for this cycle.

### Test Reports
Upon completion of each testing cycle, a report is generated in TestRail summarizing:

Total test cases executed
Pass percentage
Failures and blocked test cases
Coverage status


<br>


## Defect Management

### Reporting Bugs
Defects identified during testing are logged in JIRA with the following details:

Issue Type: Bug
Priority: Blocker, Critical, Major, Minor, Trivial
Description: Clear description of the issue.
Steps to Reproduce: Detailed steps to recreate the issue.
Expected Result: What should happen.
Actual Result: What actually happened.
Attachments: Screenshots, videos, logs if necessary.

### Issue Tracking
Once a bug is logged in JIRA, it is assigned to the relevant developer.
The bug's status is updated throughout its lifecycle (e.g., Open, In Progress, Resolved, Closed).
All resolved bugs are verified during regression testing before being marked as Closed.


<br>


## Contributing
We welcome contributions from the community to improve our testing efforts! If you'd like to contribute:

Fork the repository.
Create a new branch for your feature or bug fix.
Write or update test cases in TestRail.
Log any bugs found in JIRA.
Submit a pull request with a detailed description of the changes.
Please ensure that all contributions align with our testing standards and guidelines.



<br>


## License
This project is licensed under the MIT License - see the LICENSE file for details.

If you have any questions or need further information, feel free to reach out. Happy testing!

You can further adjust the README to fit any additional specific information or workflows you have in the project.
