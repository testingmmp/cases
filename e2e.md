##Little know Details on End to End Testing
Unlike System Testing, End-to-End Testing not only validates the software system under test but also  checks it's integration with external interfaces. Hence, the name "End-to-End". The purpose of End-to-End Testing is to exercise a complete production-like scenario. Along with the software system, it also validates batch/data processing from other upstream/downstream systems.

End to End Testing is usually executed after functional and system testing. It uses actual production like data and test environment to simulate real-time settings. End-to-End testing is also called Chain Testing


##Why End to End Testing ?
 

Modern software systems are complex and are interconnected with multiple sub-systems

A sub-system may be different from the current system or may be owned by another organization.  If any one of the sub-system fails, the whole software system could collapse. This is major risk and can be avoided by End-to-End testing. End-to-End testing verifies the complete system flow. It increase test coverage of various sub-systems. It helps detect issues with sub-systems and increases confidence in the overall software product.

 

##End to End testing Process:
The following diagram gives an overview of the End to End testing process.

The chief activities involved in End to End Testing are -

>- Study of end to end testing requirements
>- Test Environment setup and hardware/software requirements
>- Describe all the systems and its subsystems processes.
>- Description of roles and responsibilities for all the systems
>- Testing methodology and standards
>- End to end requirements tracking and designing of test cases
>- Input and  output data for each system
 

##How to create End-to-End Test Cases?


End to End Testing Design framework consists of three parts

Build user functions
Build Conditions
Build Test Cases
Let's look at them in detail: -

###Build User Functions
Following activities should be done as a part of build user functions:

List down the features of the system and their interconnected components
List the input data, action and the output data for each feature or function
Identify the relationships between the functions
Determine whether the function can be reusable or independent
 

For example -Consider a scenario where you login into your bank account and transfer some money to another account from some other bank (3rdparty sub-system)

Login into the banking system
Check for the balance amount in the account
Transfer some  amount from your account to some other bank account (3rdparty sub-system)
Check the your latest account balance
Logout of the application
 

###Build Conditions based on User Function
Following activities are performed as a part of build conditions:

Building a set of conditions for each user function defined
Conditions include sequence, timing and data conditions
 

For example -Checking of more conditions like

Login Page

Invalid User Name and Password
Checking with valid user name and password
Password strength checking
Checking of error messages
Balance Amount

Check the current balance after 24 hours.(If the transfer is sent to different bank)
Check for the error message if the transfer amount is greater than the current balance amount
 

###Build Test Scenario
Building the test scenario for the user function defined

In this case,

Login into the system
Check of bank balance amount
Transfer the bank balance amount
 

###Build Multiple Test cases
Build one or more test cases for each scenario defined .Test cases may include each condition as single test case.

 

##Metrics for end to end testing:
 

Following are few of many metrics used for End to End Testing.

Test Case preparation status: It gives Test Case preparation progress against planned
Weekly Test Progress- Provides week-wise details of percentage test completion- Failed, not executed & executed against planned for execution tests.
Defects Status & Details- It gives Percentage of open & closed defects by week. Also, week-wise defects distribution based on severity and priority
Environment Availability -Total number of hours "up" / Total number of hours scheduled per day for testing



> Written with [StackEdit](https://stackedit.io/).