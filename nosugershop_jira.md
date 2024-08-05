# Testing Project for **NoSugerShop**

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application

**Application under test**: ***NosugerShop.ro***

**Tools used**: Jira, Zephyr Squad.
## 1. Functional specifications:

The stories attached [here](https://github.com/Nadia22ST3/Testare_Manuala/blob/main/Jira_Stories.doc) were created in Jira and describes the functional specifications of the "**_Favorite_**" module, for which the final project is performed upon.

![image](https://github.com/Nadia22ST3/Testare_Manuala/assets/172371046/c7347f6c-bd50-4571-95c4-5318e2892f4d)
![image](https://github.com/Nadia22ST3/Testare_Manuala/assets/172371046/7dab7167-57c9-41e8-954c-81f429f8b3b6)

**Here you can find the release that was created for this project**:

![releases](https://github.com/user-attachments/assets/2d3c905d-5dbb-4aea-81d4-c2b7d616251e)

## 2. Testing process
The test process was performed based on the standard test process as described below.

**1.1 Test planning**

The Test Plan is designed to describe all details of testing for add favorite module from the ***NoSugerShop*** e commercial application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan. 

The test plan that was created for this project can be found [here](https://github.com/Nadia22ST3/Testare_Manuala/blob/main/Plan%20de%20Testare%20final%20.docx)

#### 1.1.1. Roles asigned to the project and persons allocated
<table>
<tr><td>Project manager </td><td>Ion Popescu</td> </tr>
<tr><td>Product owner</td><td>Cusnir Dana</td></tr>
<tr><td>Software developer</td><td>Stanescu Dan</td></tr>
<tr><td>QA Engineer</td><td>Robu Nadia</td></tr>
</table>

#### 1.1.2 Entry criteria defined

1. Business requirements are completed by the analysis team and are delivered to the appropriate testing team for evaluation.
2. The roles must have been allocated.
3. Potential project risks are detected and mitigated.
4. Roles and responsibilities are allocated.
5. The entry criteria and exit criteria must be defined.
6. Test plan should be finalized before entering the next phase of testing
   
#### 1.1.3 Exit criteria defined

1. 90%  or more of the tests are passed
2. No critical issues have status open
3. Not finding bugs of major severity in a specific period of time
4. The deadline was reached
5. The objectives were fulfilled
6. The product usage documentation has been finalized with the scenarios evaluated during the testing phase
7. Test completion report has been created and sent to the stakeholders
8. The deadline has been reached


#### 1.1.4 Test scope

In order to fulfill the testing objectives we are only going to focus on the ***Favorite*** Module which has been placed in the scope of testing and has been targeted for improvement over the next two months.

From the point of view of the testing techniques we are going to use ***dynamic*** testing especialy use ***Black-box Testing*** with the following test design techniques:

  ##### Use Case Testing
  
> This testing technique based on user actions and goals. Focuses on real-world scenarios and user stories. Helps identify gaps in functionality that might not be apparent from other testing methods.

  ##### State Transitioning
   
> In that case a software system can exist in various states (logged in, logged out, shopping cart empty, shopping cart full). Clicking "Add to Cart" while logged out should not transition to a "Shopping Cart Full" state. The system might prompt the user to log in first. Clicking "Login" while logged out should transition to the "Logged In" state, allowing access to user account features.

Also, we are going to use ***static*** testing techniques aspecialy ***Review***
It`s a software testing technique that involves examining documents by a group of individuals to identify defects and improve overall test quality.

From a testing type perspective we are going to use ***non-functional testing*** where we are going to cover only **usability testing** and **compatibility testing**. Also, positive testing and negative testing are to be done, and (according to the needs) retesting and regression testing will be done when defects are going to be fixed or when modifications of any type are going to be brought to the code.

Tests not in scope: We are not going to cover during the testing process any techniques related to **white-box testing**. Also, performance and security testing will not be performed during this session of testing.From the perspective of the modules covered, any other functionality that is located outside of the login or favorite module are not to be tested.

#### 1.1.5 Risks detected

> **Project risks**: There were no project risks throughout the testing. All entry criteria have been correctly assigned.
>
>**Product risks**: During the entire process of testing the favorites/card mode, which integrates with the login/registration mode, I did not observe any major defects. A defect can be considered that when you try to put a larger quantity of pieces in the basket, the system does not allow you, it does not inform you what quantity is in stock, it gives you an error message like Limited stock - unavailable in the requested quantity. But this aspect was not included in the requirements of the user manual of the application

#### 1.1.6 Evaluating entry criteria
The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.


### 1.2 Test Monitoring and Control
The monitoring and control stage is an essential component of any successful project. Through the effective implementation of this stage, deadlines and budgets were ensured and respected, problems were identified and fixed, good decisions were made in time, which led to increased satisfaction of interested parties and improved processes for future projects.

test metrics 

![daily test execution progress](https://github.com/user-attachments/assets/97f88299-7f64-4616-b968-5c94a91018ba)

 
### 1.3 Test Analysis
The testing process will be executed based on the application requirements.
The requirements analysis has been done in order to implement the early testing test principle and the results can be found here:

![test executions by test cycle](https://github.com/user-attachments/assets/b95b3b1d-2cd0-4918-8149-166a24fe41ee)
The following 10 test conditions were found: 
![test ](https://github.com/user-attachments/assets/26c79c56-8856-4fe6-bdf4-abafdaa894eb)

### 1.4 Test Design

Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed [here](https://github.com/Nadia22ST3/Testare_Manuala/blob/main/Jira_cases%20final.doc)


### 1.5 Test Implementation

The following elements are needed to be ready before the test execution phase begins:

In this stage of testing the test data is created, the stability of the test environment is evaluated, the existence of access to the application is checked.
### 1.6. Test Execution

Test cases are executed on the created test Cycle summary:

![cycle summary](https://github.com/user-attachments/assets/e1af1a5e-01c6-44fd-8e49-bc75bd198dd5)

Bugs have been created based on the failed tests. The complete bug reports can be found [here](https://github.com/Nadia22ST3/Testare_Manuala/blob/main/bug.doc):

![bug](https://github.com/user-attachments/assets/c58676f5-8b14-4f42-bcab-01c73523ad9c)

- ST3NR - 32 - PRIORITY HIGH, SEVERITY MEDIUM
- ST3NR - 33 - PRIORITY HIGT, SEVERITY MEDIUM
- ST3NR - 34 - PRIORITY HIGT, SEVERITY MEDIUM
  
Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

### 1.7 Test Completion
As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team

The traceability matrix was generated and can be viewed in extended format[here](https://github.com/Nadia22ST3/Testare_Manuala/blob/main/Forward%20Traceability_5_8_2024.xlsx): 

![Traceability matrix](https://github.com/user-attachments/assets/7c19411f-6933-4753-bef0-a7183e1e3978)


Test execution chart was generated and can be found below.

![dashboards](https://github.com/user-attachments/assets/befabe02-0fd4-4929-a811-365d99563fc9)


The final report shows that a number 0 tests have failed of a total of (10)

A number of 4 total bugs were found, from which the priority is: HIGT

# Conclusion of Favorites Module Testing

Based on the test cases described above, I can draw the following conclusions about the Favorites module:

> Core functionality works as expected:

        > Users can successfully add unique products to their favorites list.
        
        > Duplicates are prevented.
        
        > The quantity can be changed within the favorites list.
        
        > Quantity changes are correctly reflected in the interface.

> The module offers an intuitive user experience:

        > The process of adding products to favorites is simple and clear.

        > The quantity management options are easy to find and use.

        > Visual feedback is clear and informative.

> There is good coverage of test cases:

        > The test cases addressed a variety of possible scenarios, including adding unique products, preventing duplicates, changing quantity, and removing products.
        
        > No major functionality issues were identified.

***Recommendations***:

> Additional testing may be helpful in the following areas:

        Performance testing with a large number of products in the favorites list.
        
        Testing compatibility with various devices and web browsers.
        
        Testing error and exception scenarios.

> Implementing additional functionality could improve the Favorites module:

        Allowing users to organize products into categories or lists.
        
        Integration with other features of the application, such as shopping list or order history.
        
        Providing options to share your favorite lists with others.

