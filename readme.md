# BuyMore
## Revision History
| Date          | Description   | Author           | Comments     |
| ------------- | ------------- | ---------------- |--------------|
| 01.10.2024    | Test Plan v1  | Cornel Marcu     |versiunea 1.1 |

## Table of Content:

1. Introduction
   
   1.1 Project objective

   1.2 Functionalities in scope

   1.3 Functionalities and tests out of scope

3. Test process
   
   2.1 Test planning

   2.2 Test analysis

   2.3 Test design

   2.4 Test implementation

   2.5 Test execution

   2.6 Test closure

   2.7 Test monitoring and control

4. Test deliverables
   
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
   * Non-functional testing such as stress, performance, security and maintenance falls outside the scope of this project.
   * No QA support for mobile applications developed. Only web applications will be tested.

Automation testing is beyond scope.

## 2. Test process

### 2.1. Test planning
###2.1.1. Roles and responsibilities
| Name | Testing Scope|
|------|---------------|
|Marcu Cornel - QA Junior |Will test : User Interface, login function, Catalog |

### 2.1.2. Entry criteria

   * Roles and responsibilities for the project are allocated;
   * Functional business specifications are defined;

### 2.1.3. Exit criteria

   * 100% of tests are executed;
   * 90% of tests are passed;
   * No Critical defects have Open status;
   * User Add functionality tests are 100% passed;
   * Exploratory testing was performed on user atribute;

### 2.1.4. Risks
#### Priject Risks:
   * The risk of team members committing human errors at various stages of the project, including testing activities.
   * The risk that one or more team members may become unavailable, thus affecting the progress of the project.
   * Uncertainty or lack of communication following testing or the review process, leading to delays or misunderstandings of identified issues.

#### Product Risks:
   * Stability risks (crashes, disconnects, etc.);
   * IE browser might have performance issues;
   * The web page pagination could be impacted when opened on mobile devices;
   * Stress conditions might impact the web application;
   * New browser might not be supported;
## 2.2 Test Analysis
   * Examine the business requirements thoroughly to ensure that all necessary details are gathered for formulating the test conditions;
   * Identify the functional requirements for each functionality, including what data can be modified, what data can be deleted, and what new customer data can be added.

## 2.3 Test design
   * All test cases are written and then examined.
   * Jira will be used as the test management tool.
   * Zephyr squad will be used as a plugin for Jira.
## 2.4 Test implementation
   * All the test data is available and reviewed (Test data=email examples, password examples, employee, user with admin role);
   * Testing environment is up and running.
   * Cycle summary was created.
   * Test cases were added to the cycle summary.
   * In the implementation phase, tests are created and prepared for execution. However, regression testing, focusing on high-priority tests, will be conducted in later stages as part of the overall testing process.

## 2.5 Test execution
   * The tests will be executed on the latest versions of browsers: Chrome. If time permits, we will expand the testing scope to include other browsers;
   * Bugs (Defects) will be created based on the failed test cases;
   * Retesting will be done after a bug is fixed.
   * The full regression testing will be done after new application changes;
   
## 2.6. Test closure
   * At least 90% of tests are passed;
   * There are no critical issues in an open status;
     
## 2.7 Test monitoring and control

   * Various periodic reports will be generated to reflect the current status of the testing process.
   * Offering feedback to the QA team and other stakeholders regarding the progress.
   * All test cases are written and reviewd.
   * If significant issues arise, appropriate control measures will be implemented;
   * Prioritize testing efforts in a different way.
   * Restructure the test environment.
   * Reprioritize the test case and conditions.

## 3.Test deliveries
### 3.1. Test plan
[BuyMore](https://github.com/CornelMarcu/Buymore.ro/blob/main/Test%20plan%20Buymore%201.pdf)

### 3.2. Test conditions
The test conditions will be created based on the business requirements validated in the test analysis phase and will represent the features to be tested and transformed into test cases.
[Epic file](https://github.com/CornelMarcu/Test/blob/main/Epic.png)

[Stories nr 1 link](https://github.com/CornelMarcu/Test/blob/main/Story-user%20interface.png)

[Stories nr 2 link](https://github.com/CornelMarcu/Test/blob/main/story-ordering.png)

[Tasks nr1 link](https://github.com/CornelMarcu/Test/blob/main/t1.png)

[Tasks nr2 link](https://github.com/CornelMarcu/Test/blob/main/t2.png)

[Tasks nr3 link](https://github.com/CornelMarcu/Test/blob/main/t3.png)


### 3.3. Test cases
[Test cases](https://github.com/CornelMarcu/Test/blob/main/3.3%20Test%20steps.pdf) 

### 3.4. Daily/Weekly/Monthly test summary report
[Daily report](https://github.com/CornelMarcu/Test/blob/main/3.4%20Daily%20report.png)

### 3.5. Traceability matrix
[Traceability Matrix](https://github.com/CornelMarcu/Buymore.ro/blob/main/TRACEABILITY%20MATRIX.png)

### 3.6. Test case results
[Test case results](https://github.com/CornelMarcu/Test/blob/main/3.6%20Test%20result.pdf)

### 3.7. Bugs report
[Bugs report](https://github.com/CornelMarcu/Test/blob/main/3.7%20Bug%20report.pdf)

### 3.8. Test completion report
[Completion report](https://github.com/CornelMarcu/Buymore.ro/blob/main/Test%20execution-final.png)


### 3.9. Schedule
We will have 10 days of testing;
We have 20 test cases;
In order to finish the test run, we would need to run around 2 test per day.
