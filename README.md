## Spring Boot microdservices Code - Keep Note

### Description

In this case study KeepNote, we will implement JWT (JSON Web Token) . JSON Web Token (JWT) is an open standard (RFC 7519) that 
defines a compact and self-contained way for securely transmitting information between parties as a JSON object. This information can be verified and trusted because it is
digitally signed.

In this project, we will create this application in five parts 
    
        1. AuthenticationService
        2. UserService
        3. NoteService
        4. CategoryService
        5. ReminderService

### Steps to be followed:

    Step 1: Clone the code in a specific folder on your local machine and import the same in your eclipse STS.
    Step 2: Go thru the readme.md file and implement the code for AuthenticationService and run the test cases.
    Step 3: Go thru the readme.md file and implement the code for UserService and run the test cases.
    Step 4: Go thru the readme.md file and implement the code for NoteService  and run the test cases.
    Step 5: Go thru the readme.md file and implement the code for CategoryService and run the test cases.
    Step 6: Go thru the readme.md file and implement the code for ReminderService and run the test cases.

### Project structure

The folders and files you see in this repositories, is how it is expected to be in projects, which are submitted for automated evaluation by Hobbes

    Project
	|
	├── AuthenticationService                   // This is the microservice for User Authentication
	├── NoteService                             // This is the microservice of Note   
	├── CategoryService                         // This is the microservice of Category   
	├── ReminderService                         // This is the microservice of Reminder   
	├── UserService                             // This is the microservice of User   
	├── .gitignore			                    // This file contains a list of file name that are supposed to be ignored by git 
	├── .hobbes   			                   
	├── .project			                    // This is automatically generated by eclipse, if this file is removed your eclipse will not recognize this as your eclipse project. 
	└── pom.xml 			                    // This is the parent POM, which holds all the microservice projects.

> PS: All lint rule files are by default copied during the evaluation process, however if need to be customizing, you should copy from this repo and modify in your project repo

### Run Application
 1. To run the application you need to run all the 5 servers i.e each microservices either in sts using termineal.
 2. First check the result using postman and the use it in integration with angular.
