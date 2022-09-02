# Taxi-service

Simple wep-application that supports authentication, registration and CRUD operations.

# Application functionality

- registration 
- authentication 
- create/update/remove manufacturers;
- create/update/remove cars;
- create/update/remove drivers;
- link/unlink driver to/from car;
- display list of all manufacturers, cars, drivers

# Technologies used:

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
4) In ConnectionUtil change properties "URL", "USERNAME", "PASSWORD", "JDBC_DRIVER" (if needed) for building the appropriate connection and requests to DB
5) to open the app go to web-browser "http://localhost:8080/" and register as driver to enter
