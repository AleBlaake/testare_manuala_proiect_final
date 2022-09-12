<h1>Orange Hrm Testing Checklist</h1>

The scope of testing for Orange Hrm application is to perform various tests to ensure the quality reliance of the application.

Application under test: <a href="https://opensource-demo.orangehrmlive.com">Orange Hrm</a>

Api documentation: <a href="https://orangehrm.github.io/orangehrm-api-doc">Orange Hrm Api</a>

The testing will be divided in three sections: Gui Testing, Api Testing, SQL

Tools used for this project: MySQL Workbench, Jira, Zephyr, Postman




<h1>Functional specifications</h1>
The functional specifications for Orange Hrm platform were defined by the bussines analysis team and they cover the full description of the functionality that is expected to be fulfilled by the application.<br><br>
The bussines specifications for this application can be found <a href="https://www.orangehrm.com">here</a>


<h1>1. Gui Testing</h1>

The testing of the application from GUI perspective was done following the seven phases of the testing process as detailed below. The testing phases will be detailed only in this section dedicated for Gui Testing since the other types of testing follow the same process.

<h2>1.1 Test Planning</h2>

The test planning is the first phase of the testing process and it envolves activities that are meant to prepare the activities associated with the testing of the application and to define the item to be tested, the types of testing to be performed and the personnel responsible with testing, as well as the resources and schedules of the testing and the project risks that are identified in the scope of the product creation.


<h3>Roles for people assigned for this project</h3>

<ul>
  <li>Bussines analyst: Mirica Adrian</li>
  <li>Project manager: Dumitru Alexandru</li>
  <li>Software developer: Mandache Manuela</li>
  <li>QA Engineer: Istrati Alexandra</li>

</ul>


<h3>Entry criteria</h3>

In order to start the testing process we need fulfill the following Entry criteria:

<ul>
  <li>Bussines requirements are completed</li>
  <li>The necessary roles are assigned to the project
  <li>The deadline is defined and accepted by all parties</li>
  <li>The initial project risks are detected and mitigated</li>
    
</ul>

<h3>Exit criteria</h3>

<ul>
  <li>The tests are exectuted</li>
  <li>A low density of new high severity / high priority defects</li>
  <li>All detected bugs are fixed and closed and Regression testing showed ther ewas no negative impact over the application</li>
  <li>There were no new major product risks that were detected or existing product risks that were not mitigated</li>
</ul>



<h3>Tests in scope</h3>

<ul>
  <li>Functional testing</li>
  <li>Blackbox testing: Equivalence partitioning, Boundary Value Analysis, Decision table</li>
  <li>Compatibility testing</li>
  <li>Usability testing</li>
</ul>



<h3>Risks detected</h3>

<ol>
  
  <li>Project risks:</li>
  <ul>
    <li>Lack of experience of the Qa team</li>
    <li>short deadline of the Zephyr application</li>
    <li>lack of interaction with the development team</li>
  </ul>
  <li>Product risks
    <ul>
      <li>The abundance of the Hr platforms available on the market</li>
    

</ul>
  </li>
  </ol>


<h2>Test Monitoring and Control</h2>
For the Monitoring and control phase the following report was monitored between may and june of 2022


![](https://user-images.githubusercontent.com/109094693/179553437-d68a9482-40c9-419a-8ef1-7cb32b29ddf7.png)


<h2>Test Analysis</h2>
The testing process will be executed based on the above requirements. The follwowing test conditions were created:

<ul>
  
  <li>FA-24 - Verify user is able to add "termination reasons"</li>
  <li>FA-21 - Verify that Admin can create a new "Reporting Methods"</li>
  <li>FA-22 - Verify user can click the "cancel" button on adding a reporting methods</li>
  <li>FA-23 - Verify user si able to clic the "delete" button on Reporting Methods</li>
  <li>FA-20 - Verify Admin is able to import data from CSV file into the Configuration module</li>
  <li>FA-18 - Verify Admin is able to ADD a Custom Field</li>
  <li>FA-19 - Verify user is able to "delete" a custom field</li>
  <li>FA-17 - Verify admin is able to configure the "optional fields"</li>
  <li>FA-16 - Veify the Admin is able to delete a user </li>
  <li>FA-14 - Verify System User List</li>
  <li>FA-13 - Verify that the Hr Admin can create a User Role</li>
  <li>FA-12 - Verify the structure of the Admin Module</li> 
  
</ul>


<h2>Test design</h2>

Functional test cases were created in Zephyr Squad based on the conditions defined in the previous steps. The test design techniques used to defined the test cases were: Blackbox testing techniques, especially functional testing and exploratory testing.

The following is a list of test cases that were created in the scope of the project: [test case check list](https://github.com/AleBlaake/testare_manuala_proiect_final/files/9133783/ZFJ-Cycles-07-18-2022.csv)


The following is a list of test cases for API that were created in the scope of the project: [API check list](https://github.com/AleBlaake/testare_manuala_proiect_final/blob/main/ORANGE%20HRM.postman_collection.json) 


<h2>Test Implementation </h2>

The following elements were prepared for the Test Execution phase:

<ul>
  <li>Test enviroment: https://opensource-demo.orangehrmlive.com</li>
  <li>Access credentials: Admin / admin123</li>
  <li>Cycle Summary was created: [ZFJ-Cycles-07-18-2022(2).csv](https://github.com/AleBlaake/testare_manuala_proiect_final/files/9550015/ZFJ-Cycles-07-18-2022.2.csv)</li>
  <li>Test cases were added to the Cycle summary</li>
  <li>Test data was prepared</li>
  </ul>
  
  <h2>Test Execution</h2>
  The test cases were executed based on the above Cycle summary
  The following bugs were found:
  
  <ul>
  
  <li>FA-25] User is not able to upload e cvs file </li>
  <li>FA-26] Employee list tab is highlitghted by default</li>
  <li>[FA-27] Unexpected message returns after requesting vacation</li>
  <li>[FA-28] Adding the attachmet on "qualification", an error is shown " required" overlaps</li>
  <li>[FA-29] User is not informet about the limit of the comment that he can write</li>
  <li>[FA-30] Comments section from "Manage Performance Tracker Log " has not a limit of characters </li>
  <li>[FA-31] Bachelor degree option, from "Education" > "Add" appears 2 times</li>
  <li>[FA-32] Error message is shown "413 Request Entity Too Large" when user
    uploads a document bigger than 1MB on the "Add Job Title" section</li>
  <li>[FA-33] Supervisor not recognized when addind a review request</li>
  
  </ul>
  
  The full descrption of the bug reports were added in the folowing file: [List of bug reports](https://github.com/AleBlaake/testare_manuala_proiect_final/files/9550141/Jira.pdf)
  
  Full regression testing is needed after fixing the bugs.
  
  
  <h2>Test Completion</h2>
  
  As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team
  The traceability matrix was generated and can be found here: [Orange Hrm Traceability matrix](https://github.com/AleBlaake/testare_manuala_proiect_final/files/9550190/EXPORT.JIRA.Forward.Traceability_22_6_2022.xlsx)

  Test execution chart was generated, the final report shows that a number 2 tests have failed of a total of 14
  A number of 14 test cases were planned for execution and all of them were executed
  A number of 8 total bugs were found







