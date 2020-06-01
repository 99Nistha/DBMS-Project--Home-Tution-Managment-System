# DBMS-Project--Home-Tution-Managment-System

ABSTRACT
The project is aiming for development of home tuition system for the students of any age group by the college students. This project aims at providing benefits to both learners and tutor by giving employment  and managing skills to college students who can explore their knowledge as a tutor and ease for the students by getting knowledge from the people of same age group at their place. So, a Tuition Management System ease the work of both tutors and learners. All the required information can be obtained at single place. This system will allow the students to get independent choices they can made for the subjects and select timing from the available classes. The student can register themselves on the website and get insights of the classes and pay the fee with any of the available option.


NISTHA AGARWAL    (170425)



CHAPTER-1
 INTRODUCTION
This home tuition system allows you to manage a large number of students every day. Monitoring the presence of students and other personal information. This project aims to develop an online home tuition management system that provides the necessary and easy way to manage information daily.
1.1 PROJECT OBJECTIVES AND OBJECTIVES:
The aim of the project is to develop a home school management system. Which have a web browser interface and a database backend. The system will allow tutors to more effectively manage records and store all relevant information in one place. A key aspect of the project is that the database must be secure due to the sensitive nature of the information that could be stored. It should also allow the  users to search the information in the database in a variety of ways. From finding and contacting members of a particular learning group to keeping track of specific students.
The main objectives are therefore set:
    1. Simplifying the management of learning groups.
    2. Development of a web-based system with backend database
    3. To store and retrieve student information in one place
    4. Development of a system that is safe due to the sensitive nature of the stored information
    5. Development of a suitable search function to meet the needs of the user
1.2 INTRODUCTION OVERVIEW
The project objectives are well defined, but although these goals are the key features that the project should meet, these are not the only potential features that a home management system could have. There is room for many other features. Possible other extensions are:
     1.   Reports manifestations.
     2.   Other users who can search the data for useful information. 
     3.   Complex search function.
CHAPTER-2
BACKGROUND AND LITERATURE SURVEY
The project must consider the GUI from the perspective of human-computer interaction so that the web application can be used as easily as possible. Attention should be paid to colors, consistency and navigation. The project must also be safe and the development should take into account all possible forms of attack. If the encoding permits, security vulnerabilities should be kept as low as possible. This includes reviewing the data to minimize security risks to the system. The use of PHP and MySQL in combination with HTML, CSS and possibly various other client-side scripting languages ​​allows the successful implementation of the above.
2.1 SECURITY
Security is one of the main concerns when it comes to web applications. One of the recent high-profile cases occurred earlier this year, when hackers launched cyber attacks on Gmail's Google email service. Security should not be an afterthought in web design. The end user will always assume that the website he or she uses is safe, that their data is not displayed to anyone, and the passwords are secure.
2.2 LANGUAGES AND DATABASE:
The security discussion thus leads to the main programming language and database that can be selected to build the application. Language and database combination will allow the best performance as well as the required security are:
2.2.1 NetBeans:
NetBeans is an integrated development environment (IDE) for Java. With NetBeans, applications can be developed from a range of modular software components known as modules. NetBeans runs on Microsoft Windows, Mac OS, Linux and Solaris. In addition to Java development, there are extensions for other languages ​​such as PHP, C, C ++, HTML5 and Javascript. NetBeans-based applications, including the NetBeans IDE, can be extended by third-party developers.


2.2.2 MySQL: 
MySQL is by far the most popular database management system for small to medium web projects. Only the proprietary Oracle database and the small embeddable SQLite are being distributed.
MySQL is by far the most popular database management system for small to medium web projects. Only the proprietary Oracle database and the small embeddable SQLite are being distributed.
A database is a place where data of various types can be stored for later retrieval. You can vary in size from a single table to large collections of tables with millions of tuples and columns. It is not expected that the project should require a database with more than several tables or so (
There was only one real consideration in choosing a database, namely the use of MySQL. The reasons are as follows:
1. Compared to Oracle or Microsoft SQL Server immediately available and available for free.
2. Is often used by many organizations.
3. Provides good performance, reliability, portability and stability.
4. Easily manipulated with PHP with many online books and user guides.
JDBC connector:
The Java Database Connectivity (JDBC) Connector is a program that allows Java application servers running on the Sun Microsystems Java 2 platform, Enterprise Edition (J2EE), to access different databases. The JDBC Connector connects an application server to a JDBC driver. With the connector, driver providers can pack drivers to be plug-and-play with J2EE applications. In addition, application server manufacturers may allow the use of third-party JDBC drivers for their products.



CHAPTER-3
DESIGN
3.1 DATABASE DESIGN:
The database is designed to store the raw data identified in the requirement collection phase. To design the database structure, an entity relationship model (ER) must be created to visualize the structure of the database. The ER model describes data as entities, relationships, and attributes. The first element in an ER model is an entity that represents physical objects in the real world, be it a person, an object or a structure. Each entity then becomes a table in the database. For the new system 6 entities are identified:
User (who can log in to the system)
Each entity has one or more attributes that describe it. These attributes each have values ​​that are the raw data v alues ​​that the database contains.
Each entity has a set of attributes:
The students have a student ID, a first name, a last name, a user name, an e-mail address, a study program, a gender, a status, a tutoring group and a tutorial group.
Groups of teachers have a group ID, a teacher's name, a room, an email for the tutor, a second tutor, and a second email for the tutor.
Database attributes can be either compound or atomic. Composite attributes are those that consist of more than one value.
If an entity references another entity, we have a relationship within the database. The relationships themselves are not attributes, but allow us to show how entities within the database connect. Relationships are often depicted as a diamond in the ER model. To facilitate our mathematical understanding of relationships, a cardinality ratio is used to indicate the maximum number of relational instances an entity can participate in.
3.2 DESIGN OVERVIEW:
The design of the new system is now in force. The visual aspects of the site have been chosen to maximize the use of color and the user's intuition. The layout of the site is designed to minimize the number of clicks a user must make to reach a required goal. The database is designed to minimize redundant data and maximize relationships to easily retrieve the required raw data for the user.


Figure 3(a): The database ER Model



CHAPTER-4
RESULTS AND CONCLUSIONS
The chapter discusses the Home Tuition Management System and its intended use. This chapter first describes the main page and then goes through the entire system. This begins with uploading data and stakeholder participation and then organizing meetings with students and tutor groups.
The application initially starts with a simple login page that verifies the user's credentials. The login page first verifies that the user data in the database matches before accepting or denying the login attempt. The home page contains the main navigation bar at the top of the page to access all areas of the application.
The body of the page displays new messages from students. The user has the ability to respond immediately by clicking on the student's name or performing other tasks before responding to those queries. These messages are not removed unless the user responds to the individual sender.
A) Navigation menu
C) Password change
B) Messages from students
D) create / reset student registration
To the right of the body, there is the possibility that the primary user may change his own password for security reasons. Underneath is the function "Create student account". This allows the user to give students access to their own attendance data and to verify that their personal information is correct. If a student has forgotten their password, an e-mail request can be sent to the main user to request a password reset.
             

REFERENCE
Bibliography
Center, T. M. (2014). Tuition Management Systems. Retrieved from SECURITY: https://www.valpo.edu/it/2016/01/11/tuition-management-systems-student-account-center/
Modelling, E. R. (2016). An Intelligent Tutoring System for Entity Relationship Modelling. Retrieved from ER MODEL: https://telearn.archives-ouvertes.fr/hal-00197310/document
TMS. (2014). TMS. Retrieved from Tuition Management Systems: http://www.tuitionmanagementsystems.com/
TUTOR, P. M. (2017). PROJECT MANAGMENT TUTOR. Retrieved from RESULT: https://www.findtutorsnearme.com/subject/project-management/







