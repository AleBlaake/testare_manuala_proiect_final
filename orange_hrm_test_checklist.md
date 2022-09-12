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

The following is a list of test cases that were created in the scope of the project.

[test case check list](https://github.com/AleBlaake/testare_manuala_proiect_final/files/9133783/ZFJ-Cycles-07-18-2022.csv)












