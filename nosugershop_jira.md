# Testing Project for **NoSugerShop**

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application

Application under test: ***NosugerShop.ro***

Tools used: Jira, Zephyr Squad.
## Functional specifications:

The below stories were created in Jira and describes the functional specifications of the "**_Favorite_**" module, for which the final project is performed upon.

![image](https://github.com/Nadia22ST3/Testare_Manuala/assets/172371046/c7347f6c-bd50-4571-95c4-5318e2892f4d)
![image](https://github.com/Nadia22ST3/Testare_Manuala/assets/172371046/7dab7167-57c9-41e8-954c-81f429f8b3b6)


**Here you can find the release that was created for this project**:


(![image](https://github.com/Nadia22ST3/Testare_Manuala/assets/172371046/067c1749-1b0f-4449-9c12-b90ae4e96c72)


The test process was performed based on the standard test process as described below.

**1.1 Test planning**

The Test Plan is designed to describe all details of testing for all the modules from the ***NoSugerShop*** application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan. 

The test plan that was created for this project can be found here 

 **((https://bentoteam-my.sharepoint.com/:w:/g/personal/nadia_robu_bento_ro/EVDgClNLZm5LqeecDW4eVXQBd21QZLTuvJKl2YWCyyM5UQ?e=w7B1eV))**

*_1.1.1. Roles asigned to the project and persons allocated*_

(numele persoanelor pot sa fie fictive, doar sa treceti numele vostru ca si tester)

    Project manager - Datcu George
    Product owner - Cusnir Dana
    Software developer - Stanescu Dan 
    QA Engineer - Robu Nadia

*_1.1.2 Entry criteria defined*_:

1. Testing environment is up and running.
2. Business requirements are completed by the analysis team and are delivered to the appropriate testing team for evaluation.
3. The roles must have been allocated.
4. Potential project risks are detected and mitigated.
5. Roles and responsibilities are allocated.
6. The entry criteria and exit criteria must be defined.
7. Test plan should be finalized before entering the next phase of testing

*_1.1.3 Exit criteria defined*_:

1. 90%  or more of the tests are passed
2. No critical issues have status open
3. All detected errors have been reported and closed
4. The budget was reached
5. The deadline was reached
6. The objectives were fulfilled
7. The product usage documentation has been finalized with the scenarios evaluated during the testing phase
8. Test completion report has been created and sent to the stakeholders
9. Product risks have been identified and mitigated

*_1.1.4 Test scope*_

In order to fulfill the testing objectives we are only going to focus on the ***Favorite*** Module which has been placed in the scope of testing and has been targeted for improvement over the next two months.

From the point of view of the testing techniques we are going to use ***dynamic*** testing aspecialy use ***Blackbox Testing*** with the following test design techniques:
1. **Use Case Testing**
- This testing technique based on user actions and goals. Focuses on real-world scenarios and user stories. Helps identify gaps in functionality that might not be apparent from other testing methods.
    and
2. **State Transitioning**
   
- In that case a software system can exist in various states (logged in, logged out, shopping cart empty, shopping cart full). Clicking "Add to Cart" while logged out should not transition to a "Shopping Cart Full" state. The system might prompt the user to log in first. Clicking "Login" while logged out should transition to the "Logged In" state, allowing access to user account features.

Also, we are going to use ***static*** testing techniques aspecialy ***Review***
It`s a software testing technique that involves examining documents by a group of individuals to identify defects and improve overall test quality.

From a testing type perspective we are going to use ***non-functional testing*** where we are going to cover only **usability testing** and **compatibility testing**. Also, positive testing and negative testing are to be done, and (according to the needs) retesting and regression testing will be done when defects are going to be fixed or when modifications of any type are going to be brought to the code.

Tests not in scope:

We are not going to cover during the testing process any techniques related to **whitebox testing**.

Also, performance and security testing will not be performed during this session of testing.

From the perspective of the modules covered, any other functionality that is located outside of the login or favorite module are not to be tested.

*_1.1.5 Risks detected*_

**Project risks**: There were no project risks throughout the testing. All entry criteria have been correctly assigned.

**Product risks**: During the entire process of testing the favorites/card mode, which integrates with the login/registration mode, I did not observe any major defects. A defect can be considered that when you try to put a larger quantity of pieces in the basket, the system does not allow you, it does not inform you what quantity is in stock, it gives you an error message like Limited stock - unavailable in the requested quantity. But this aspect was not included in the requirements of the user manual of the application

*_1.1.6 Evaluating entry criteria*_
The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

**1.2 Test Monitoring and Control**
The monitoring and control stage is an essential component of any successful project. Through the effective implementation of this stage, deadlines and budgets were ensured and respected, problems were identified and fixed, good decisions were made in time, which led to increased satisfaction of interested parties and improved processes for future projects.

Aici veti insera de asemenea si raportul de status (test status report) din zephyr - test metrics - primul din lista care sa reflecte activitatea si evolutia testarii. Recomand aici sa executati teste aproape in fiecare zi ca sa vada angajatorul implicarea voastra in testare)

 
**1.3 Test Analysis**
The testing process will be executed based on the application requirements.
The requirements analysis has been done in order to implement the early testing test principle and the results can be found here:

![image](https://github.com/Nadia22ST3/Testare_Manuala/assets/172371046/3b641302-4c64-4232-a6fd-2499d692e5e7)
![image](https://github.com/Nadia22ST3/Testare_Manuala/assets/172371046/36ab2b9f-2d1b-48b0-8651-9cbddf8eb8ed)

1.4 Test Design

Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed here  

https://bentoteam-my.sharepoint.com/:b:/g/personal/nadia_robu_bento_ro/EWv1U3Gvlr5IlYhwB77QirEBlVQjLGSp-QRG2FEGzbSagg?e=ak5VJH

1.5 Test Implementation

The following elements are needed to be ready before the test execution phase begins:

(inserati lista de elemente care sunt evaluate in etapa de implementare)
***1.6. Test Execution***

Test cases are executed on the created test Cycle summary: (inserati aici numele cycle-ului pe care l-ati creat)

Bugs have been created based on the failed tests. The complete bug reports can be found here: (inserati aici fisierul cu bug-urile pe care le-ati identificat)

The following is a summary of the bugs that have been found (inserati o lista cu titlurile bug-urilor identificate impreuna cu prioritatea si severitatea fiecaruia)

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

***1.7 Test Completion***
As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team

The traceability matrix was generated and can be found here: 

(![image](https://github.com/Nadia22ST3/Testare_Manuala/assets/172371046/d6dcf7c3-7c92-4c4f-b3d7-016bce77e41c)

Test execution chart was generated and can be found below.

![image](https://github.com/Nadia22ST3/Testare_Manuala/assets/172371046/10249d30-7071-4dfb-897e-f022be1663ed)


The final report shows that a number () tests have failed of a total of (inserati numarul de teste)

A number of (inserati numarul de bug-uri) total bugs were found, from which the priority is: (inserati numarul de bug-uri) are high and (inserati numarul de bug-uri) are medium.

(inserati aici o concluzie generala a testarii care sa cuprinda cate teste au fost create si executate, ce procentaj aproximativ din cerintele in scop au fost acoperite, daca exista vreo functionalitate pe care nu ai apucat sa o testezi, daca bug-urile gasite impacteaza lansarea produsului in productie sau se pot fixa si ulterior, daca ai identificat riscuri de produs care trebuie mitigate, daca e vreo reecomandare pe care vrei sa o faci pentru lansare, daca sunt ceva lessons learned de care trebuie sa se tina cont la proiectele viitoare etc.)
