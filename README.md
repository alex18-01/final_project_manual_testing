<h1>Testing Project for epantofi.ro</h1>

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application

Application under test: https://epantofi.ro/

Tools used: Jira, Zephyr Squad.

<h2>Functional specifications:</h2>

The below stories were created in Jira and describe the functional specifications of the module, for which the final project is performed upon.

![story_wishlist](https://github.com/alex18-01/final_project_manual_testing/assets/152299946/d18fbed6-8572-4c08-ad37-75d011235a1d)
![story_filtre](https://github.com/alex18-01/final_project_manual_testing/assets/152299946/3db34d96-a355-4b61-a50c-f42c23993ad1)


Here you can find the release that was created for this project:

![release_jira](https://github.com/alex18-01/final_project_manual_testing/assets/152299946/02912d49-e21f-4b43-bc4b-36545662c897)


<h2>Testing process</h2>

The test process was performed based on the standard test process as described below.

<h3>1.1 Test planning</h3>

The **Test Plan** is designed to describe all details of testing for specific features of the website epantofi.ro:
- **Implement a Wishlist Functionality for users**
- **Implement Search Filters for products**

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan. 

<h4>1.1.1. Roles asigned to the project and persons allocated</h4>

<ul>
  <li>Project manager - John Smith</li> 
  <li>Product owner - Thomas Brown</li>
  <li>Software developer - Emily Graham</li>
  <li>QA Engineer - Andrei Alexandru Busuioc</li>
</ul>

<h4> 1.1.2 Entry criteria defined </h4>

1. **Implement a Wishlist Functionality for users:**
   - **Completion:** The development of the wishlist feature is completed and the feature is deployed in the test environment.
   - **Design**: UI/UX designs for the wishlist feature are finalized and approved.

2. **Implement Search Filters for products:**

   - **Completion:** The development of the search filters feature is completed and the feature is deployed in the test environment.
   - **Filter Criteria:** Define and agree upon the criteria for product filters (size, color, brand, price range etc.) and ensure they are documented.
   - **Design**: UI/UX designs for the wishlist feature are finalized and approved.

<h4> 1.1.3 Exit criteria defined </h4>

   - **Test Case Execution:** All predefined test cases for both the wishlist functionality and product filters have been executed.
   - **Regression Testing:** Regression testing has been conducted to ensure that existing functionalities are not affected by the new features.
   - **Performance Testing:** Performance testing has been completed for both the wishlist functionality and product filters.
   - **Documentation:** All testing, including test plans, test cases, test results, and logs, are thoroughly documented.
   - **User Acceptance Testing (UAT):** Both the wishlist functionality and product filters have passed User Acceptance Testing by relevant stakeholders.

<h4> 1.1.4 Test scope</h4>

<h5> Tests in scope: </h5>

 - Test the ability to add, remove various products to the wishlist.
 - Test that users can view all items in their wishlist.
 - Test that wishlist items persist across user sessions (for logged in users).
 - Verify that filtering products by various filters returns the correct results.
 - Test that combined filters return accurate results.
 - Test that the product list returns to the default state when filters are cleared.

<h5>Tests not in scope: </h5>

 - Security Testing
 - Performance Testing
 - Unit Testing 


<h4>1.1.5 Risks detected</h4>

<h5>Project risks:</h5>

  - **Communication Issues:** Ineffective communication among the team members, stakeholders, or between development and testing teams.
  - **Lacking Resources:** Insufficient availability of resources for development, testing, or other project activities.
  - **Delays:** Unforeseen challenges or scope changes that lead to project delays.


<h5> Product risks: </h5>

- **Wishlist Inaccuracy:** Inaccurate results in a user's wishlist.
- **Search Filters Inaccuracy:** Inaccurate results in a user's search due to filters.
- **Usability Issues:** Poor user experience due to usability issues.


<h4>1.1.6 Evaluating entry criteria</h4>

The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

<h3>1.2 Test Monitoring and Control<h3>

Generating periodic reports that reflect the current status of the testing process will provide transparency and reduce possible delays.

![test execution report](https://github.com/alex18-01/final_project_manual_testing/assets/152299946/dd00e311-05f6-4fa0-b8cf-64e42a25ada1)


**Test Execution Completion Over Cycles by Status:**

- Cycle 1: 20% tests failed, 80% passed.
- Cycle 2: 100% pass rate.
- Cycle 3: 100% pass rate.

<h3> 1.3 Test Analysis </h3>
The testing process will be executed based on the application requirements.

The following test conditions were found: <br>

![lista_testcases](https://github.com/alex18-01/final_project_manual_testing/assets/152299946/1d441235-c5bf-4b03-b362-ad8dc18f2452)


<h3>1.4 Test Design</h3>

Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed here: [testcases.xlsx](https://github.com/user-attachments/files/15522291/testcases.xlsx)


<h3>1.5 Test Implementation</h3>

The following elements are needed to be ready before the test execution phase begins:

- **Test Environment:** A stable test environment is set up with the latest build that includes the wishlist feature.
- **Test Environment:** A stable test environment is set up with the latest build that includes the search filters.
- **Test Data**: Relevant test data (credentials, products) are available in the test environment.

* The test cases have been written
* The story was implemented and was deployed to the testing environment
* The Chrome/Firefox/Safari/Opera browsers are installed
* The tester has a good internet connection
* The tester is using a laptop or PC with Windows 10/11


<h3>1.6. Test Execution </h3>

Test cases are executed on the created Test Cycle summary.

Bugs have been created based on the failed tests. The complete bug reports can be found here: [bugreports.pdf](https://github.com/user-attachments/files/15522295/bugreports.pdf)


The following is a summary of the bugs that have been found:
* The Button "X" for removing a filter can't be pressed
* There's been an error while trying to login

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

<h3>1.7 Test Completion </h3>
As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team

The traceability matrix was generated and can be found here: 

![traceabilitymatrix](https://github.com/alex18-01/final_project_manual_testing/assets/152299946/e706b29c-157e-494f-9a17-166c82036d43)


Test execution chart was generated and can be found below. 

![test execution report](https://github.com/alex18-01/final_project_manual_testing/assets/152299946/55202388-f8b3-4a16-8afb-0d3f3bb9322f)


The final report shows that a number 2 tests have failed of a total of 10, but after the second test cycle 0 tests failed.

A number of 2 total bugs were found, from which the priority is: one is high and one is medium, both were resolved after the first test cycle.


<h3>General Conclusion</h3>
The manual testing efforts for the wishlist functionality and product filters on Epantofi.ro have been comprehensive and detailed. 
By adhering to a thorough testing scope and addressing all identified risks, we have achieved a high level of confidence in the quality and reliability of these features. This comprehensive approach ensures that the new functionalities will deliver a positive user experience, contributing to increased customer satisfaction and engagement on Epantofi.ro.
