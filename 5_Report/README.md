## Report

 #  Description
 * A Employee Record Management system is a software built to handle the primary housekeeping functions of a company. It help companies keep track of all the employees and their records. It is used to manage the company using computerized system.
 
 # Requirements


 ## High Level Requirements
 |ID  |DESCRIPTION                                                        |STATUS     |
 |:---|:------------------------------------------------------------------|:----------| 
 |HLR1|The Application should allow user to enter info.                   |Implemented|
 |HLR2|The Application should allow user to list all the employee records |Implemented|
 |HLR3| The Application should allow user to modify the employee record   |Implemented|
 |HLR4| The Application should allow user to delete employee records      |Implemented|
 |HLR4| The Application should allow user to exit from application        |Implemented|


 ## Low Level Requirements
 |ID  |DESCRIPTION                                                        |STATUS     |
 |:---|:------------------------------------------------------------------|:----------|
 |HLR1|The application ask use to choose between 1 to 5                   |Implemented|
 |    |1.Add Record                                                       |           |
 |    |2.List Record                                                      |           |
 |    |3.Modify Record                                                    |           |
 |    |4.Delete Record                                                    |           |
 |    |5.Exit                                                             |           |
 |HLR2|The application will ask user to enter info such as Enter name, Enter Salary,and Enter Age|Implemented|
 |HLR3|The application will show all details of employees                 |Implemented|
 |HLR4|The application will ask user enter name (for modifying)           |Implemented|
 |HLR5|The application will ask user to enter name (for deleting)         |Implemented|

 ## SWOT Analysis

 # Strengths
 * Simple & Easy to Use.

 * Efficient Cloud Data Management.

 * Highly Secure, Scalable & Reliable.

 * Mobile Access.

 # Weaknesses
 * The data stored is prone to cyber hacks.

 * Costly and Expensive.

 * Complicated to operate.

 * Online Systems require high-speed internet connectivity.

 * Risk of computer virus.

 # Opportunities

 The Employee record management leaks outward into new spaces, spaces which it didn’t inhabit before, such as reading ,modify and delete the records of employees.
  
# Threats
Employee Record sytem now send and retrieve data from databases to help better manage inventory and the like, but some libraries don’t have the right data encryption practices in place. This can often lead to lost data and sometimes, the data easily obtainable by criminals.



## 4W'S & 1H

# Who
This Employee Record Management System is an application is used by all the Employees who are having id's.

# What:
 Employee Record Management Systems is software that helps to maintain a database that is useful to enter new name &  other records of the members.

# When:
This Employee Record Management System is very useful when there are large no of employees working in an organization. It is very tedious to enter the records manually so here this project come into handy.

# Where:
The Employee Record management system is nowadays essential for all type of organizations. 

# How:
This project is implemented for storing the employee information,modifying and delete the records.
# Architecture
##Structural Diagrams
## High Level
![structure_high](https://user-images.githubusercontent.com/98841253/153236512-53ac1ec4-fc1b-4420-b34a-133365a8405d.JPG)

## Low Level
![structure_low](https://user-images.githubusercontent.com/98841253/153236764-a7ef4dd7-1194-423f-8cbc-75f556df81c3.JPG)
## Behavioral Diagrams
## High Level
![FlowChart](https://user-images.githubusercontent.com/98841253/153235467-9bfa8b5b-4699-4c30-b671-34c9305a8009.png)
## Low Level
![Behave_low](https://user-images.githubusercontent.com/98841253/153236224-8f0315d8-8fb3-48f7-abb0-d87c7e6dad20.JPG)
# Test Plan 

TEST ID| TEST CASE OBJECTIVE| INPUT DATA   | EXPECTED OUTPUT| ACTUAL OUTPUT| STATUS|
|:-----|:-------------------|:-------------|:---------------|:-------------|:------|
|TC_1  |for entering name   |enter name:abc|  xyz           | xyz          |PASS   |
|TC_2  |for entering name   |enter name:abc|xyz             |-             |FAIL   |
|TC_3  |for entering age    |enter age:22  |22              |22            |PASS   |
|TC_4  |for entering age    |enter age:22  |22              |-             |FAIL   |
|TC_5  |for entering salary |enter salary:10000|10000       |10000         |PASS   |
|TC_6  |for entering salary |enter salary:10000|10000       |-             |FAIL   |
|TC_7  |for listing record  |xyz 22 10000  |xyz 22 10000    |xyz 22 10000  |PASS   |
|TC_8  |for listing record  |xyz 22 10000  |xyz 22 10000    |xyz 10000 22  |FAIL   |
|TC_9  |for listing record  |xyz 22 10000  |xyz 22 10000    |22 xyz 10000  |FAIL   |
|TC_10 |for deleting record |xyz           |xyz             |xyz           |PASS   |
|TC_11 |for deleting record |xyz           |xyz             |pqr           |FAIL   |
## Images and Videos
# Images
# Adding Employees Information
![list](https://user-images.githubusercontent.com/98841253/153535323-62246dd0-2039-431e-9049-7e28a112a020.jpg)


# Listing Employee Information
![delete](https://user-images.githubusercontent.com/98841253/153535487-3266ffe1-66a4-4bf2-9f14-b57182e9f0cb.jpg)


# Deleting Employee Information
![exit](https://user-images.githubusercontent.com/98841253/153550684-de8a2375-0000-47cf-a734-cd980467c362.jpg)


# Exiting From Application
![add](https://user-images.githubusercontent.com/98841253/153535224-124282bb-6225-430c-bf17-61327b0e169d.jpg)

## References
[Reference_1](https://followtutorials.com/2011/08/mini-project-employee-record-system-using-c.html)

[Reference_2](https://github.com/raagavardhini/Stepin-Employee-Record-System)






