About

A secure banking system (SBS) is a software system developed primarily to facilitate secure banking transactions and user account management through the Internet. A banking organization often needs to track various operations performed by both the internal and external users using the organization’s banking infrastructure. The focus of this project is to develop a SBS to facilitate secure banking transactions and account management required by any banking organization.




Application Overview

This report documents our work for the 50.531 Secure Software Engineering final project. In this project, we were distributed a running but incomplete web application for a bank - bankwebapp. This project is coded in java, using the IntelliJ environment on the Apache Tomcat 8.0 server as localhost. The distributed project allows users to register accounts and login. Additionally, there is a default username, staff_1 with administrative privileges. The key objectives for this project are

Completion of the functionalities including transactions and batch transactions
Implementation of security features
Testing the project's source codes for defects
Testing the project's source codes for vulnerabilities.
Additionally, we will apply USE cases and USE case diagrams to show demonstrate our direction and logic flow.



Features Implementation

Onboarding New User
One of the key features we have implemented beyond the scope of the deliverables and rubrics we have added is a stringent requirement for registration credentials. We would require that for registration, users

Use a password with at least one uppercase, one digit (0-9), one symbol and at least 8 characters long.
Use a valid email address.
Users would require a valid username, password and email address for login. As these are standard security implementations adopted by most public platforms, we opine that it was a good practice to implement this for our project as well. You may refer to the Security Implementations section below for a full discussion.
