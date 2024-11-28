QAfox.com Testing Project
This project involves both Manual Testing and Automation Testing of the QAfox.com application.
The manual testing phase includes the creation of various test documents, while the automation testing phase leverages Cypress with the Page Object Model (POM) design pattern.

Introduction
The QAfox.com Testing Project focuses on validating the functionality, reliability, and performance of the application using Manual Testing and Automation Testing.

Manual Testing ensures the completeness of functional testing through well-documented artifacts.
Automation Testing is implemented using Cypress and follows the Page Object Model (POM) to enhance test reusability and maintainability.

Project Scope
Ensure that all features of QAfox.com are functioning as expected.
Validate edge cases, boundary values, and error-handling scenarios.
Automate regression and smoke testing to improve testing efficiency.
Provide detailed documentation for manual and automation testing processes.
Testing Approach
Manual Testing
Create and execute test artifacts such as:
📑 Project Workflow
Test Plan
Test Cases
Test Scenarios
Bug Reports
Requirements Traceability Matrix (RTM)
Test Summary and Execution Reports
Identify and report defects, ensuring accurate documentation and communication with stakeholders.

Automation Testing
Automate test cases using Cypress, following the Page Object Model (POM) approach.
Focus on:
Smoke Tests
Regression Tests
Cross-browser Testing
Generate detailed reports of test execution and performance metrics.
Testing Documentation
Test Plan
Describes the objectives, scope, tools, schedule, and resources required for testing the QAfox.com application.

Test Cases
Detailed steps for each test, including:

Test Case ID
Description
Precondition
Steps to Execute
Expected Results
Actual Results
Status (Pass/Fail)
Bug Report
Tracks issues found during testing, including:

Bug ID
Description
Steps to Reproduce
Severity & Priority
Status
Assigned To
Test Scenarios
High-level test conditions to validate the key functionalities of QAfox.com.

RTM (Requirements Traceability Matrix)
Maps test cases to requirements to ensure complete test coverage.

Test Summary Report
Summarizes the testing effort, including the number of test cases executed, passed, failed, and defects identified.

Test Execution Report
Provides details about the test execution timeline, environment, and results.

How to Run Tests
Manual Testing
Open the relevant test documentation from the ManualTesting folder.
Follow the execution steps outlined in the test cases.
Log results and defects in the appropriate reports.
Automation Testing
Clone the repository to your local machine:

git clone <repository-url>  
Install dependencies:

npm install  
Run Cypress tests:

npx cypress open  
Choose the desired test suite to execute.
For headless execution:

npx cypress run  
View test reports in the cypress/reports folder.

Technology Stack
Manual Testing Tools: Microsoft Excel, 
Automation Framework: Cypress
Programming Language: JavaScript
Design Pattern: Page Object Model (POM)
Reporting Tools: VS Code
