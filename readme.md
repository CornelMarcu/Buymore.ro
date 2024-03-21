# OpenCart
## Revision History
| Date          | Description   | Author           | Comments     |
| ------------- | ------------- | ---------------- |--------------|
| 10.03.2023    | Test Plan v02 | Cornel           |versiunea 1.1 |

1. Introdution
OpenCart, a free open-source e-commerce platform, caters to online merchants by offering a robust and dependable framework for establishing thriving digital stores. This framework is embraced by diverse users, including experienced web developers seeking a user-friendly interface and newcomers venturing into online business for the first time.
OpenCart boasts an array of features that empower you to customize your store extensively, enabling you to unlock its full potential with the aid of its tools.

1.1. Project Objective
Before releasing the project to customers, it's crucial to elevate trust in its quality to the highest level achievable.
Application being tested: https://demo.opencart.com/admin/
Documentation: https://docs.opencart.com/en-gb/administration/

1.2. Functionalities in scope
All features, functionalities, and capabilities outlined in the OpenCart business requirements for the Admin Module will be subject testing across various types, including functional testing, system testing, acceptance testing, component testing, and compatibility testing.
The OpenCart application will be tested on latest versions of Microsoft Edge, Chrome and IE browsers.

1.3 Functionalities and tests out of scope
Non-functional testing such as stress, performance, security and maintenance falls outside the scope of this project.
No QA support for mobile applications developed. Only web applications will be tested.
Automation testing is beyond scope.
All features that are not under Admin Module.

2. Test process
2.1. Test planning
2.1.1. Roles and responsibilities
Name	Testing Scope
Simona - QA Junior	will test: User Management, Dashboard, Catalog
QA Senior	will test: Design, Sales, Customers, Marketing
2.1.2. Entry criteria
Smoke test passed (being the most basic type of test, this is a very important entry criteria in the process of testing);
Testing environment is up and running;
Roles and responsibilities for the project are allocated;
Functional business specifications are defined;
2.1.3. Exit criteria
100% of tests are executed;
90% of tests are passed;
No Critical defects have Open status;
User Add functionality tests are 100% passed;
Exploratory testing was performed on Admin module;
2.1.4. Risks
Stability risks (crashes, disconnects, etc.);
IE browser might have performance issues;
The web page pagination could be impacted when opened on mobile devices;
Stress conditions might impact the web application;
New browser might not be supported;
2.2 Test Analysis
Examine the business requirements thoroughly to ensure that all necessary details are gathered for formulating the test conditions;
Write test conditions (What?);
We intend to complete a full regression test on the current version;
2.3 Test design
All the test cases (How?) are written and reviewed;
All test cases are generated within Jira, serving as our Test Management Tool;
2.4 Test implementation
All the test data is available and reviewed (Test data=email examples, password examples, employee, user with admin role);
This test run exclusively focuses on regression testing, wherein we will prioritize tests of the highest importance as our primary objective;
Create the test suites (Cycle Summary) (Grouped by release version or testing type);
2.5 Test execution
The tests will be executed on the latest versions of browsers: Chrome, Microsoft Edge, IE. If time permits, we will expand the testing scope to include other browsers;
Bugs (Defects) will be created based on the failed test cases;
The full regression testing will be done after new application changes;
Retesting will occur following the resolution of any identified bugs;
2.6. Test closure
At least 90% of tests are passed;
There are no critical issues in an open status;
2.7 Test monitoring and control
Status reports will be generated to indicate the current status of the testing process;
If significant issues arise, appropriate control measures will be implemented;
