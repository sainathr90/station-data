# station-data
This project is to allow end-users to pull station data.

Demo Application
Overview:
	This application is going to be a REST service, built with Spring Boot, to allow end-users to pull station data. Please store application in a public repository that I will have access to. Granular commits are required. Although the application is small and shouldn’t require many, I would like you to perform multiple commits to the repository. I would suggest and initial commit with the application downloaded from the below website and then make commits for any changes to any application layers that you are working on.
You can build a starter application at http://start.spring.io. Select the packages that are needed and import the rest through Gradle.
Create a Spring Boot application that meets the following criteria
1.	Includes the following dependencies
a.	Gradle
b.	Swagger(UI documentation Tool)
c.	Jacoco(Code Coverage)
d.	Junit
e.	Accuator(Bind to separate port)
f.	H2 Database
g.	MyBatis(ORM)
2.	Functional requirements
a.	User must be able to access API endpoints and retrieve data
b.	User must be able to add a station
c.	User must be able to remove a station
d.	User must be able to update a station
e.	User must be able to search by stations by station ID or name
f.	User must be able to search HD enabled stations
g.	Code coverage must be at least 80%
3.	Non Functional
a.	Must be a scalable application
b.	Should perform searches quickly
Bonus:
1.	Implement FlyWay for DB Versioning
2.	Use Lombok for Getter/Setter annotations
3.	100% Code Coverage
4.	Docker implemented
If you have any questions please feel free to reach out to me. You don’t have to create a UI or specific users on this just test that the endpoints are working as intended and have to the proper Unit Tests created for the application.

