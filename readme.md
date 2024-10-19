# BuyMore
## Revision History
| Date          | Description   | Author           | Comments     |
| ------------- | ------------- | ---------------- |--------------|
| 01.10.2024    | Test Plan v1  | Cornel Marcu     |versiunea 1.1 |

1.Introduction

1.1 Project objective

1.2 Functionalities in scope

1.3 Functionalities and tests out of scope

2. Test process
   
2.1 Test planning

2.2 Test analysis

2.3 Test design

2.4 Test implementation

2.5 Test execution

2.6 Test closure

2.7 Test monitoring and control

3. Test deliverables
   
3.1 Test plan

3.2 Test conditions

3.3 Test cases

3.4 Daily test summary reports

3.5 Traceability matrix

3.6 Test case results

3.7 Bugs report

3.8 Test completion report


## 1. Introdution
Buy More. Ro is an online store for Romanians, with delivery exclusively on the territory of Romania. Since its establishment – 2017, our team aims to come in front of customers with the best quality-price ratio for the products sold. We carefully choose the products listed on Acasa and maintain the quality of the products, constantly diversifying the range of products.

So far, we have managed to cover an important segment of the market: basic clothing. With the help of our customers, we have identified the biggest needs in the niche and adapted so that we can also offer quality experiences, not just quality products at fair prices. We identified the biggest fear of customers in this niche: the fear of not choosing the right size. Thus, on Acasa you benefit from free, simple and fast returns. The free return is also a guarantee for the quality of the products.

Also, by actively listening to the needs of customers, we have discovered that more and more
### 1.1. Project Objective
Before releasing the project to customers, it's crucial to elevate trust in its quality to the highest level achievable.

Application being tested: https://buymore.ro/

Documentation: https://buymore.ro/despre-noi/

### 1.2. Functionalities in scope
All features, functionalities, and capabilities outlined in the BuyMore business requirements for the customer's point of view will be subject testing across various types, including functional testing, system testing, acceptance testing, component testing, and compatibility testing.
The BuyMore application will be tested on latest versions of Google Chrome. 

### 1.3 Functionalities and tests out of scope
Non-functional testing such as stress, performance, security and maintenance falls outside the scope of this project.
No QA support for mobile applications developed. Only web applications will be tested.
Automation testing is beyond scope.

## 2. Test process
### 2.1. Test planning
###2.1.1. Roles and responsibilities
| Name | Testing Scope|
|------|---------------|
|Marcu Cornel - QA Junior |Will test : User Interface, login function, Catalog |

### 2.1.2. Entry criteria
Smoke test passed (being the most basic type of test, this is a very important entry criteria in the process of testing);
Testing environment is up and running;
Roles and responsibilities for the project are allocated;
Functional business specifications are defined;
### 2.1.3. Exit criteria
100% of tests are executed;
90% of tests are passed;
No Critical defects have Open status;
User Add functionality tests are 100% passed;
Exploratory testing was performed on user atribute;
### 2.1.4. Risks
Stability risks (crashes, disconnects, etc.);
IE browser might have performance issues;
The web page pagination could be impacted when opened on mobile devices;
Stress conditions might impact the web application;
New browser might not be supported;
## 2.2 Test Analysis
Examine the business requirements thoroughly to ensure that all necessary details are gathered for formulating the test conditions;
Write test conditions (What?);
We intend to complete a full regression test on the current version;
## 2.3 Test design
All the test cases (How?) are written and reviewed;
All test cases are generated within Jira, serving as our Test Management Tool;
## 2.4 Test implementation
All the test data is available and reviewed (Test data=email examples, password examples, employee, user with admin role);
This test run exclusively focuses on regression testing, wherein we will prioritize tests of the highest importance as our primary objective;
Create the test suites (Cycle Summary) (Grouped by release version or testing type);
## 2.5 Test execution
The tests will be executed on the latest versions of browsers: Chrome, Microsoft Edge, IE. If time permits, we will expand the testing scope to include other browsers;
Bugs (Defects) will be created based on the failed test cases;
The full regression testing will be done after new application changes;
Retesting will occur following the resolution of any identified bugs;
## 2.6. Test closure
At least 90% of tests are passed;
There are no critical issues in an open status;
## 2.7 Test monitoring and control
Status reports will be generated to indicate the current status of the testing process;
If significant issues arise, appropriate control measures will be implemented;


## 3.Test deliveries
### 3.1. Test plan
[BuyMore](https://github.com/CornelMarcu/Test/blob/main/Test%20plan%20Buymore.pdf)

### 3.2. Test conditions
The test conditions will be created based on the business requirements validated in the test analysis phase and will represent the features to be tested and transformed into test cases.
[Epic](https://github.com/CornelMarcu/Test/blob/main/Epic.png)

[Stories]1.(https://github.com/CornelMarcu/Test/blob/main/Story-user%20interface.png)

[Stories]2.(https://github.com/CornelMarcu/Test/blob/main/story-ordering.png)

[Tasks]1.(https://github.com/CornelMarcu/Test/blob/main/t1.png)

[Tasks]2.(https://github.com/CornelMarcu/Test/blob/main/t2.png)

[Tasks]3.(https://github.com/CornelMarcu/Test/blob/main/t3.png)


### 3.3. Test cases
[](https://github.com/CornelMarcu/Test/blob/main/3.3%20Test%20steps.pdf) 

### 3.4. Daily/Weekly/Monthly test summary report


### 3.5. Traceability matrix
Link to Traceability Matrix: link

### 3.6. Test case results
Link to Test case results: 

### 3.7. Bugs report
Link to Bugs report: 

### 3.8. Test completion report
Completionreport


### 3.9. Schedule
We will have 10 days of testing;
We have 30 test cases;
In order to finish the test run, we would need to run around 3 test per day.
