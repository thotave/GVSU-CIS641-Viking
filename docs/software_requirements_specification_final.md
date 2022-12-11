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
| FR2 | For sign-in, user need to have the user detail (email and password). |
| FR3 | User sign-in shall be failed if he gives wrong information.  |
| FR4 | User email address shall be unique. |
| FR5 | User shall be given choice of recovering account if he forget password. |
| FR6 | Admin shall be able to login using email and password. |

### Sign Up/User Registration:

| ID | Requirement|
| :-------------: | :----------: |
| FR7 | Sign-up screen shall be displayed when the user clicks the sign-up button. |
| FR8 | After clicking on sign up option, page should display the options of name, email address , phone number, home address, date of birth and password to fill. |
| FR9 | User details shall be captured.  |
| FR10 | Error should be thrown if a invalid data is given.  |
| FR11 | Sign-up form inputs shall be validated when the user clicks submit button. |


### Upload documents:

| ID | Requirement|
| :-------------: | :----------: |
| FR12 | When user successfully login into the system there will be an option to upload your documents. |
| FR13 | When user clicks on upload the document button a new page will be open. |
| FR14 | In new page there will be document upload control and a field named as document tittle. |
| FR15 | When user selects files and enters title then users will be able to upload the doc in the system. |
| FR16 | After validation document will be uploaded and success message will appear. |

### Attendance Management:

| ID | Requirement|
| :-------------: | :----------: |
| FR17 | When users successfully login into the system his/her attendance shall automatically marked and entry time shall be recorded into the system |
| FR18 | There shall be a button to take break and when user clicks on this button the time for break shall record. |
| FR19 | There shall be a button to resume work and when user clicks on this button the end time of break shall record.|
| FR20 | When user clicks on logout button the shift shall be ended|
| FR21 | Number of hours worked shall be recorded after shift is ended|

### Operational Requirements:

| ID | Requirement|
| :-------------: | :----------: |
| FR22 | After successful login, dashboard shall appear |
| FR23 | There shall be an option to upload the documents. |
| FR24 | There shall be an option to take break/ resume work |
| FR25 | There shall be an option to check her current week hours and salary |
| FR26 | Admin shall be able to view all the employees name |
| FR27 | Admin shall be able edit employees details |
| FR28 | Admin shall be able to view employees details like work hours, break taken |

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
| NFR8 | User shall be able to access the login page within minimal time of application started |
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
| NFR16 | User's personal data shall be stored in database in an encrypted format. |
| NFR17 | Unsuccessful login of user shall be recorded and audited. |
| NFR18 | User data shall not be shared with any other third party servers. |
| NFR19 | The source coding shall follow secure coding practices. |
| NFR20 | User's credentials shall be stored in an encrypted format |
| NFR21 | System shall not crashed after continuously running for more than 24 hours |


### Performance:

| ID | Requirement|
| :-------------: | :----------: |
| NFR22 |The system shall be capable of handling multiple users at a time. |
| NFR23 | System shall upload the documents within minimal time |
| NFR24 | System shall provide high performance to it's users|
| NFR25 | System shall be able to provide all the functionalities without application getting crashed |
| NFR26 | Backend server shall be running until system is closed. |

# Change management plan

This section will describe a change management plan for Employee Management System. It will focus on training users, platform availability, performance and issues handling and resolving process.

## How will you train people to use EMS system?
1. **Provide a comprehensive overview of the system:** Explain the purpose and importance of the system for an organization, its features, how secured it is and how it can benefit the organization. 
2. **Demonstrate how to use the system:** Show users how to use and navigate the system, enter data, and access reports. 
3. **Provide hands-on practice:** Allow users to practice using the system in a safe environment. 
4. **Offer support:** Make sure users have access to help when they need it.


## How Employee Management system will you ensure it integrates within their ecosystem / software?
1. Identify the existing software and systems that the company is currently using and determine how the employee management system will be helpful and need to integrate with them. 
2. Develop an integration plan that outlines the steps needed to integrate the employee management system with the existing software and systems. 
3. Create an API that will allow the employee management system to communicate with the existing software and systems. 
4. Test the integration to ensure that the employee management system is working properly with the existing.


## How Employee Management system will you ensure that it any discovered issues are resolved?
* **Monitor system performance:** Monitor the performance of the system on a regular basis to identify any potential issues.
* **Establish a process for reporting and tracking issues:** Establish a process for employees to report any issues they discover with the system. 
* This process should include a way to track the issue, assign it to the appropriate support team, and provide updates on the progress of the resolution. 
* A designated contact person or team receives it and respond to reports. 
* **Create a timeline for resolution:** Establish a timeline for resolving any issues that are reported. This timeline should include a deadline and details about how the work can be finished and when the issue can be resolved.
* The best way to ensure that any issues that are discovered in an Employee Management System are resolved is to have a comprehensive bug tracking system in place. 
* This system should include a way to track reported bugs, prioritize them, assign responsible parties, and track their resolution.
* Additionally, regular audits of the system should be conducted to detect and resolve any issues that arise. 
* Finally, providing employee feedback systems and regular customer satisfaction surveys can help to identify the issues and get them resolved.

# Traceability links

This section represents relationship between requirements and other project artifacts such as class diagram, Use case diagram and activity diagram.

## Use Case Diagram Traceability

| Artifact ID | Artifact Name | Requirement ID |
| :-------------: | :----------: | :------------: |
|1| [Sign In/Login](https://github.com/thotave/GVSU-CIS641-Vikings/blob/master/artifacts/User%20Case%20diagrams.pdf) | FR1-FR7 |
|2| [Registration](https://github.com/thotave/GVSU-CIS641-Vikings/blob/master/artifacts/User%20Case%20diagrams.pdf) | FR8-FR11 |
|3| [Use Case DEscription](https://github.com/thotave/GVSU-CIS641-Vikings/blob/master/artifacts/Use%20case%20Description.pdf) | FR2, FR12-FR16 |


## Class Diagram Traceability

| Artifact ID | Artifact Name | Requirement ID |
| :-------------: | :----------: | :------------: |
|1| [User](https://github.com/thotave/GVSU-CIS641-Vikings/blob/master/artifacts/Class%20Diagram%20EMS.pdf) | FR22, FR23, FR24, FR25, NFR3, NFR5 |
|2| [Admin](https://github.com/thotave/GVSU-CIS641-Vikings/blob/master/artifacts/Class%20Diagram%20EMS.pdf) | FR25, FR26, FR27, FR28 |
|3| [Upload doc](https://github.com/thotave/GVSU-CIS641-Vikings/blob/master/artifacts/Class%20Diagram%20EMS.pdf) | FR12-FR16, NFR2, NFR3 |

## Activity Diagram Traceability


| Artifact ID | Artifact Name | Requirement ID |
| :-------------: | :----------: | :----------: |
|4| [Employee Signup](https://github.com/thotave/GVSU-CIS641-Vikings/blob/master/artifacts/Activity%20Diagrams.pdf) | FR1-FR11, NFR2 |
|4| [Start Work](https://github.com/thotave/GVSU-CIS641-Vikings/blob/master/artifacts/Activity%20Diagrams.pdf) | FR17-FR21, NFR2 |


# Software Artifacts

<Describe the purpose of this section>

1. [Employee interface, HR interface - Use case diagram combined](https://github.com/thotave/GVSU-CIS641-Vikings/blob/master/artifacts/User%20Case%20diagrams.pdf)
2. [Use case description](https://github.com/thotave/GVSU-CIS641-Vikings/blob/master/artifacts/Use%20case%20Description.pdf)
3. [Sign up, registration - Activity Diagram](https://github.com/thotave/GVSU-CIS641-Vikings/blob/master/artifacts/Activity%20Diagrams.pdf)
4. [Start wprk - Activity diagram](https://github.com/thotave/GVSU-CIS641-Vikings/blob/master/artifacts/Activity%20Diagrams.pdf)
5. [EMS Class diagram](https://github.com/thotave/GVSU-CIS641-Vikings/blob/master/artifacts/Class%20Diagram%20EMS.pdf)
6. [EMS Class diagram description](https://github.com/thotave/GVSU-CIS641-Vikings/blob/master/artifacts/Class%20diagram%20description.docx)
7. [EMS Sequence diagram](https://github.com/thotave/GVSU-CIS641-Vikings/blob/master/artifacts/Employee-Management-System-Sequence-Diagram.webp)
