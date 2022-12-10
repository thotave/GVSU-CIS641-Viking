# Overview:

The software requirement specification document outlines the requirements of Vikings project, Employee Management System. This document explains about the system's features, interfaces and design logic in details. 

# Software Requirements
This section of the document focuses on how the system shall response and what all services are available to the EMS users. 
Functional requirements section covers details of user requirements.
Non-functional requirement section provides a user expectation and applies to whole system

## Functional Requirements

### Manage User Login:

| ID | Requirement |
| :-------------: | :----------: |
| FR1 | Upon completion of page loading, the welcome screen shall display sign-inscreen and sign-up button for sign-up.|
| FR2 |  Sign-up screen shall be displayed when the user presses the sign-up button. |
| FR3 | For sign-in user have to up the user detail (email and password)  |
| FR4 | Admin shall be able to login using email and password |

### Sign Up/User Registration:

| ID | Requirement|
| :-------------: | :----------: |
| FR5 | Sign-up screen shall be displayed when the user presses the sign-up button |
| FR6 | After clicking on sign up option, page should display the options of name, email , phone number, home address, password to fill |
| FR7 | users details shall be captured  |
| FR8 | Sign-up form inputs shall be validated when the user presses submit button |


### Upload documents:

| ID | Requirement|
| :-------------: | :----------: |
| FR9 | When users successfully login into the system there will be an option to upload your documents. |
| FR10 |  When users clicks on upload the document button a new page will be open. |
| FR11 | In new page the will be document upload control and a field named as document tittle. |
| FR12 | When user selects files and enters title then users will be ab le to upload the doc in the system. |
| FR13| After validation document will be uploaded and success message will appear. |

### Attendance Management:

| ID | Requirement|
| :-------------: | :----------: |
| FR14 | When users successfully login into the system his/her attendance shall automatically marked and entry time shall be recorded into the system |
| FR15 | There shall be a button to take break and when user clicks on this button the break start time shall record. |
| FR16 | There shall be a button to resume work and when user clicks on this button the break end time shall record.|
| FR17 | When user clicks on logout button the shift shall be ended|
| FR18 | Number of hours worked shall be recorded after shift is ended|

### Operational Requirements:

| ID | Requirement|
| :-------------: | :----------: |
| FR19 | After successful login, dashboard shall appear |
| FR20 | There shall be an option to upload the documents. |
| FR21 | There shall be an option to take break/ resume work |
| FR22 | There shall be an option to check her current week hours and salary |
| FR23 | Admin shall be able to view all the employees name |
| FR24 | Admin shall be able edit employees details |
| FR25 | Admin shall be able to view employees details like work hours, break taken |

## Non-Functional Requirements

### Quality:

| ID | Requirement|
| :-------------: | :----------: |
| NFR1 | All users shall have valid email address. |
| NFR2 | All users should have document in pdf format |
| NFR3 | The size of all documents should be small. |
| NFR4 | User shallnot be able to edit the time of his/her shift. |
| NFR5 | <Non-Functional Requirement 1> |
| NFR6 | <Non-Functional Requirement 2> |

### Availability:

| ID | Requirement|
| :-------------: | :----------: |
| NFR7 | Application shall be up and running unitruptly until it is closed. |
| NFR8 | User shall be able to access the login page within 5 second of application started |
| NFR9 | All the documents saved by the user shall be stored in the backend of S# bucket |
| NFR10 | After successful login, users email address, password, name , phone shall be stored in AsyncStorage. |


### Operational Requirement:

| ID | Requirement|
| :-------------: | :----------: |
| NFR11 | Application shall be installed or run on both operating systems -Windows, Linux |
| NFR12 | The system front end UI shall be created using Angular JS |
| NFR13 | System shall be build using Angular CLI |
| NFR14 | Application Shall store user's data in MongoDb |
| NFR15 | Application Shall store user's pdf documents in amazon S3 bucket|

###  Security:

| ID | Requirement|
| :-------------: | :----------: |
| NFR16 | User's personal data shall be stored in database in encrypted format. |
| NFR17 | Unsuccessful login of user shall be recorded and audited. |
| NFR18 | User data shall not be shared with any other party. |
| NFR19 | The source coding shall follow secure coding practices. |
| NFR20 | User's password shall be stored in encrypted format |
| NFR21 | System shall not crashed after continuously running for more than 24 hours |


### Performance:

| ID | Requirement|
| :-------------: | :----------: |
| NFR22 |The system shall be capable of handling multiple users at a time. |
| NFR23 | System shall upload the documents within 2 seconds |
| NFR24 | System shall provide high performance to it's users|
| NFR25 | System shall be provide all the functionalities without app getting freezed |
| NFR26 | Backend server shall be running until system is closed. |

# Change management plan

This section will describe a change management plan for Employee Management System. It will focus on training users, platform availability, performance and issue handling process.

## How will you train people to use EMS system?
1. Provide a comprehensive overview of the system: Explain the purpose of the system, its features, and how it can benefit the organization. 
2. Demonstrate how to use the system: Show users how to navigate the system, enter data, and access reports. 
3. Provide hands-on practice: Allow users to practice using the system in a safe environment. 
4. Offer support: Make sure users have access to help when they need it.


## How Employee Management system will you ensure it integrates within their ecosystem / software?
1. Identify the existing software and systems that the company is currently using and determine how the employee management system will need to integrate with them. 
2. Develop an integration plan that outlines the steps needed to integrate the employee management system with the existing software and systems. 
3. Create an API that will allow the employee management system to communicate with the existing software and systems. 
4. Test the integration to ensure that the employee management system is working properly with the existing


## How Employee Management system will you ensure that it any discovered issues are resolved?
•	Establish a process for reporting and tracking issues: Establish a process for employees to report any issues they discover with the system. 
•	This process should include a way to track the issue, assign it to the appropriate team member, and provide updates on the progress of the resolution. 
•	And a designated contact person or team to receive and respond to reports. 
•	Create a timeline for resolution: Establish a timeline for resolving any issues that are reported. This timeline should include a deadline for when the issue should be resolved and a plan for how the work should be finished.
•	Monitor system performance: Monitor the performance of the system on a regular basis to identify any potential issues.
•	The best way to ensure that any issues that are discovered in an Employee Management System are resolved is to have a comprehensive bug tracking system in place. 
•	This system should include a way to track reported bugs, prioritize them, assign responsible parties, and track their resolution.
•	 Additionally, regular audits of the system should be conducted to detect and resolve any issues that arise. 
•	Finally, providing employee feedback systems and regular customer satisfaction surveys can help to identify potential issues before they become major problems.

# Traceability links

This section represents relationship between requirements and other project artifacts such as class diagram, Use case diagram and activity diagram.

## Use Case Diagram Traceability

| Artifact ID | Artifact Name | Requirement ID |
| :-------------: | :----------: | :------------: |
|1| [Sign In/Login](https://github.com/thotave/GVSU-CIS641-Vikings/blob/master/artifacts/User%20Case%20diagrams.pdf) | FR1,FR2, FR3, FR4, FR5|
|2| [Registration](https://github.com/thotave/GVSU-CIS641-Vikings/blob/master/artifacts/User%20Case%20diagrams.pdf) | FR6,FR7, FR8, FR9, FR10|
|3|[Use Case DEscription](https://github.com/thotave/GVSU-CIS641-Vikings/blob/master/artifacts/Use%20case%20Description.pdf) | NFR7, NFR10 |


## Class Diagram Traceability

| Artifact ID | Artifact Name | Requirement ID |
| :-------------: | :----------: | :------------: |
|1| [User](https://github.com/thotave/GVSU-CIS641-Vikings/blob/master/artifacts/Class%20Diagram%20EMS.pdf) | FR19, FR20, FR21, FR22, NFR3, FR5 |
|2| [Admin](https://github.com/thotave/GVSU-CIS641-Vikings/blob/master/artifacts/Class%20Diagram%20EMS.pdf) |  FR22, FR23, FR24, FR25 |
|3| [Upload doc](https://github.com/thotave/GVSU-CIS641-Vikings/blob/master/artifacts/Class%20Diagram%20EMS.pdf) |  FR9, FR10, FR11, FR12, FR13 |

## Activity Diagram Traceability


| Artifact ID | Artifact Name | Requirement ID |
| :-------------: | :----------: | :----------: |
|4| [Employee Signup](https://github.com/thotave/GVSU-CIS641-Vikings/blob/master/artifacts/Activity%20Diagrams.pdf) | FR1-5, NFR2 |
|4| [Start Work](https://github.com/thotave/GVSU-CIS641-Vikings/blob/master/artifacts/Activity%20Diagrams.pdf) | FR14-FR18, NFR2 |


# Software Artifacts

<Describe the purpose of this section>

1. [Employee interface, HR interface - Use case diagram combined](https://github.com/thotave/GVSU-CIS641-Vikings/blob/master/artifacts/User%20Case%20diagrams.pdf)
2. [Use case description](https://github.com/thotave/GVSU-CIS641-Vikings/blob/master/artifacts/Use%20case%20Description.pdf)
3. [Sign up, registration - Activity Diagram](https://github.com/thotave/GVSU-CIS641-Vikings/blob/master/artifacts/Activity%20Diagrams.pdf)
4. [Start wprk - Activity diagram](https://github.com/thotave/GVSU-CIS641-Vikings/blob/master/artifacts/Activity%20Diagrams.pdf)
5. [EMS Class diagram](https://github.com/thotave/GVSU-CIS641-Vikings/blob/master/artifacts/Class%20Diagram%20EMS.pdf)
6. [EMS Class diagram description](https://github.com/thotave/GVSU-CIS641-Vikings/blob/master/artifacts/Class%20diagram%20description.docx)
7. [EMS Sequence diagram](https://github.com/thotave/GVSU-CIS641-Vikings/blob/master/artifacts/Employee-Management-System-Sequence-Diagram.webp)
