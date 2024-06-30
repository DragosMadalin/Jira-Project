<h1>Testing Project for **Porc**</h1>

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application

Application under test: **www.porcporc.com**

Tools used: Jira, Zephyr Squad, 
Windows Snipping Tool, Microsoft Power Point
<h2>Functional specifications:</h2>

The below stories created in Jira describes the functional specifications of the "CLIENT NOU" and "Lista Mea de dorinte" module, for which the final project is performed upon.

![story1](https://github.com/DragosMadalin/Jira-Project/assets/166251306/80f6375d-f887-4e47-8939-a4e6c4c96273)

![Story2](https://github.com/DragosMadalin/Jira-Project/assets/166251306/ed430aa6-c763-4a47-8621-7e7b584a8c83)


Here you can find the release that was created for this project:
![release](https://github.com/DragosMadalin/Jira-Project/assets/166251306/5dd18e05-d4cd-4345-8ae1-4bf21d074838)


<h2>Testing process</h2>

The test process was performed based on the standard test process as described below.

<h3>1.1 Test planning</h3>

The Test Plan is designed to describe all details of testing for all the modules from the JPetStore Demo application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan. The test plan that was created for this project can be found here https://github.com/DragosMadalin/Jira-Project/blob/main/Test%20Plan.pdf
](https://github.com/DragosMadalin/Jira-Project/blob/main/Test%20Plan.pdf)
<h4>1.1.1. Roles asigned to the project and persons allocated</h4>


<ul>
  <li>Project manager Dobrin George</li> 
  <li>Product owner Porc Inc.</li>
  <li>Software developer Catalin Dumitrescu</li>
  <li>QA Engineer Dobre Dragos Madalin</li>
</ul>

<h4> 1.1.2 Entry criteria defined </h4>

New Account
Customer Id - Customer ID is required
Customer Id - Special character are not allowed
Customer Id - Characters are not allowed
Customer Id - First character cannot have space
New Customer
Customer Name – Numbers are not allowed
Customer Name – Special characters are not allowed
Customer Name -  Customer name must not be blank
Email : Email ID must not be blank
Email : Email ID is not valid
Password:
New Password must not be blank
Enter at-least one special character
Confirm Password must not be blank
Passwords do not Match


<h4> 1.1.3 Exit criteria defined </h4>

All critical defects identified during testing are addressed and verified. 
Performance benchmarks meet predefined thresholds for response time and resource utilization. 
 Security vulnerabilities identified during testing are mitigated or documented with a resolution plan. 
Identified usability issues are addressed or prioritized for future improvements. 
Test documentation, including test cases, test results and any deviations are reviewed and finalized. 


<h4> 1.1.4 Test scope</h4>

<h5> Tests in scope: </h5>

Verify that  an user can add items in wish list
Verify that an client can change the size and color of the item
Verify that an client can remove an item from wish list
Verify that the user can add a item from his wish list to shopping cart
Verify that the user can add all of the item from wish list to his sopping cart
Verify that a new user can create a new account using only mandatory fields
Verify that a new user can create a new account using  all fields
Verify that the mandatory field is correctly displayed for invalid data

<h5>Tests not in scope: </h5>

Database testing
Automatic testing
Load testing

<h4>1.1.5 Risks detected</h4>

<h5>Project risks:</h5>

Exeding the availabe time frame
Not executing all of the test cases


<h5> Product risks: </h5>

Porc is an online platform, it is vulnerable to network issues.
Data breaches
Unauthorized access to user accounts


<h4>1.1.6 Evaluating entry criteria</h4>

The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

<h3>1.2 Test Monitoring and Control<h3>

Test Monitoring and Control

Objective: Ensure the testing process is effectively tracked and controlled to meet the project objectives and quality standards.

Activities:

Progress Tracking:

Daily/weekly status meetings to review testing progress against the schedule.
Regular updates on test case execution, defect status, and risk assessment.
Risk Management:

Continuous monitoring of identified risks.
Regular updates to the risk log and implementation of mitigation strategies.
Defect Management:

Tracking defects from identification to resolution.
Prioritizing defects based on severity and impact on the project timeline.
Test Reporting:

Daily test execution reports.
Detailed test summary reports at the end of each testing phase.
Final test report highlighting overall test results, major defects, and readiness for production.
Review and Adjustments:

Regular review of test documentation and progress.
Adjusting the test plan, schedule, and resources as needed based on ongoing progress and findings.

![test metrics 1](https://github.com/DragosMadalin/Jira-Project/assets/166251306/96438bb4-408a-4c12-8286-a2d17f100b75)
![test metric 2](https://github.com/DragosMadalin/Jira-Project/assets/166251306/28a94a37-faaf-4e0d-9fe7-c6dd21332aa5)


<h3> 1.3 Test Analysis </h3>
The testing process will be executed based on the application requirements.

The following test conditions were found: <br>
![titlu teste](https://github.com/DragosMadalin/Jira-Project/assets/166251306/8034cc8c-ff31-41db-b45f-43ad812096f8)


<h3>1.4 Test Design</h3>

Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed here https://github.com/DragosMadalin/Jira-Project/blob/main/ZFJ-issue-export-06-30-2024-6d62336ffffe8bb-0001.pdf
<h3>1.5 Test Implementation</h3>

The following elements are needed to be ready before the test execution phase begins:

**(inserati lista de elemente care sunt evaluate in etapa de implementare)**

<h3>1.6. Test Execution </h3>

Test cases are executed on the created test Cycle summary: ![cycle](https://github.com/DragosMadalin/Jira-Project/assets/166251306/f4f0737d-9191-4d0f-b9ff-0f4f7faa44ed)


Bugs have been created based on the failed tests. The complete bug reports can be found here: 

The following is a summary of the bugs that have been found
![bug poza](https://github.com/DragosMadalin/Jira-Project/assets/166251306/295b55bc-642a-42c5-a72e-7562673148b1)


Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

1.7 Test Completion
As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team

The traceability matrix was generated and can be found here: ![trasabilitate](https://github.com/DragosMadalin/Jira-Project/assets/166251306/0e68d672-7337-4bef-aaa2-7aa4c5247e8f)


Test execution chart was generated and can be found below. 
![dashboard](https://github.com/DragosMadalin/Jira-Project/assets/166251306/27e392ac-0df6-4fec-97db-aaa8107f7c15)



The final report shows that a number 10 tests have failed of a total of 1

A number of 1 total bugs were found, from which the priority is:0 are high and 1 are medium.

Only one bug were found, from which the priority is medium.

The project has successfully implemented and tested a wide range of functionality for users, with a high test execution and success rate. Five significant bugs have been identified, all of which are being resolved. Prompt resolution of these bugs will be crucial to ensure a continued robust user experience. The detailed testing and bug identification efforts have laid a solid foundation for further improvements and future development.
