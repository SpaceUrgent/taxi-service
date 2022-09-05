# Taxi-service

Simple wep-application that supports authentication, registration and CRUD operations.
By entering to the server java page register new driver as user. After registration user will be able to login
to app, manage and obtain information about cars/drivers/manufacturers stored in the database. 

# Application functionality

- registration 
- authentication 
- create/update/remove manufacturers;
- create/update/remove cars;
- create/update/remove drivers;
- link/unlink driver to/from car;
- display list of all manufacturers, cars, drivers

# Technologies used:

- Java 11
- JDBC
- Servlet
- MySQL
- Tomcat 9.0.50
- JSP
- JSTL
- Maven

# To install the app:

1) Clone the project to your machine
2) Configure Apache Tomcat: 
> Add/edit configuration &rarr;
> Add new &rarr;
> Choose TomcatServer(local) &rarr;
> In Application server field put path to folder with tomcat &rarr;
> Switch to Deployment tab and add "taxiservice:war exploded" &rarr;
> Clear Application context path to "/" &rarr;
> Select apply and Run the app 
3) Download MySQL and MySQL Workbench and excute all queries from
taxi-service/src/resources/init_db.sql to setup schema
4) In ConnectionUtil change properties "URL", "USERNAME", "PASSWORD", "JDBC_DRIVER" for building the appropriate connection and requests to DB
5) to open the app go to web-browser "http://localhost:8080/" and register as driver to enter
