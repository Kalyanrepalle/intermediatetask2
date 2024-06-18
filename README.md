# Medical Center Management System
A web-based Online Medical Center Management System for SUST Medical Center.

## Problem Statement
-----------------
Currently, the SUST Medical Centre uses a manual management system for maintaining patient demographics and distributing medicine. The existing system requires doctors and other employees to spend a significant amount of time on paperwork for tasks such as prescribing medication, delivering medicine, maintaining stock, and retrieving records. Therefore, an automated online management system is needed.

## Project Overview
----------------
This system will provide a graphical user interface to manage the entire system, including patient prescriptions, medicine distribution, and stock maintenance. The new system will be accessible from terminals within the Medical Center and via the internet from computers outside the Medical Center. Patients (both students and staff) will be able to view their prescriptions online from anywhere.

## Users
-----
1. **General User (Patient):** Student, Staff.
2. **Administrative User:** Doctor, Pharmacist, Store Officer, Medicine Distributor.

## Major Functions
---------------
The main features of this project include:
- Computerizing the entire existing management system.
- Maintaining patient diagnosis details and advised tests.
- Keeping records of patient prescriptions, medications, instructions, precautions, and diet advice.
- Providing and maintaining all records of stocked medicine in both central-store and sub-store.
- Tracking newly purchased medicine and monitoring their flow.
- Generating billing reports for employee patients.
- Providing a proposed list of medicine for upcoming purchases.
- Allowing users to retrieve forgotten passwords using a hint question.

## System Interfaces
-----------------
- **Client on Internet:** Web Browser, Operating System (any).
- **Client on Intranet:** Client Software, Web Browser, Operating System (any).
- **Web Server:** Apache Tomcat, Operating System (any).
- **Database:** MySQL.

## User Interface
--------------
User interfaces for all users are graphical and can be both web-based and desktop-based, connected to the central medical terminal. The interfaces are designed to be simple and straightforward.

## Communication Interface
-----------------------
- Clients on the Internet will use HTTP/HTTPS Protocol.
- Clients on the intranet will use TCP/IP protocol.

## Requirements & Installation
---------------------------
### Requirements:

1. JDK 6u1
2. NetBeans IDE 6.9.1
3. MySQL Database
   - MySQL 5.1.39
   - MySQL Connector ODBC 5.1.6
   - MySQL GUI Tools 5.0
4. MySQL Connector Java 5.1.6
5. Apache Tomcat 6.0.26 (integrated with NetBeans)
6. Firefox 3.6.3 or higher

### Installation:

1. Install JDK.
2. Install NetBeans IDE (Version 6.9.1).
3. Install MySQL database components. The default username and password are `root` and `admin`, respectively. To change these, modify the `database.java` file located in *project\MedicalCentre\src\java\medicalcenter*.
4. Install Firefox web browser.
5. Open NetBeans IDE and import the `MedicalCentre` project as a web project.
6. Add *mysql-connector-java-5.1.6-bin.jar* to Libraries if not already added.

### Known Issues:

Even with correct installation and configuration, you may encounter database issues. The `DBQuery.sql` file provides database queries (e.g., trigger, procedure, event) for troubleshooting.

## Dummy Users

Here are a few dummy users available in the system:

| User Name  | Password | User Type          |
|------------|----------|--------------------|
| doctor     | d        | Doctor             |
| doctor2    | d        | Doctor             |
| pharmacist | p        | Pharmacist         |
| md         | md1      | Medicine Distributor|
| a-cse      | p        | Patient (Employee) |
| b-cse      | p        | Patient (Employee) |
| 2007331039 | mokarrom | Patient (Student)  |
| 2007331023 | p        | Patient (Student)  |

## Reference
---------
A detailed technical report explaining different phases (e.g., requirement analysis, system design, architecture, coding, debugging, and testing) of software engineering is available in the `docs` directory.
