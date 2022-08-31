# taxi-service

Simple wep-application that supports authentication, registration and CRUD operations.

Please refer to   open application at Heroku

#Application functionality

- registration 
- authentication 
- create/update/remove manufacturers;
- create/update/remove cars;
- create/update/remove drivers;
- link/unlink driver to/from car;
- display list of all manufacturers, cars, drivers

#Technologies used:

- JDBC
- Servlet
- MySQL
- Tomcat 9.0.50
- JSP
- JSTL
- Maven

#To install the app:

1) clone the project to your machine
2) configure Apache Tomcat: 
add/edit configuration => Add new =>  choose TomcatServer(local) =>
in Application server field put path to folder with tomcat => 
switch to Deployment tab and add "taxiservice:war exploded" => 
clear Application context path tp "/" =>
select apply and Run the app
3) to open the app go to web-browser "http://localhost:8080/" and register as driver to enter
