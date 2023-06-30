# 🚖 Taxi-service 🚖
This is a simple application of the drivers registration system. 

The system user is the driver. The driver can sign up and if he already signed up - sign in. The driver can view all information about available cars and drivers assigned to them. Basic CRUD operations are available.

The project has an N-tier architecture and consists of the database layer, the DAO layer for interaction with the database, the service layer which contains the business logic, and the presentation layer.

## 🎯 Features
- User registration and authentication
- Create new drivers, cars, and manufacturers
- View all drivers, cars, and manufacturers
- Edit and delete existing drivers, cars, and manufacturers

## 🛠 Technologies
- JDBC
- MySQL
- Servlet API
- JSP
- JSTL
- Tomcat 11.0.0-M6
- Maven
- CSS

## ⚙️ Installation
#### To run the application, the following prerequisites are needed:

- Java 17 or later
- Apache Tomcat 10 (version 11.0.0-M6 is recommended)
- MySQL 8 or later
#### To install the application, follow these steps:

1. Clone the repository using the command git clone https://github.com/ihor-sydorenko/taxi-service
2. Open the project in your preferred IDE and build the project
3. Create the database schema and tables using the scripts provided in the src/main/resources/init_db.sql
4. In the ConnectionUtil class, change the values of the constants to your own. You need to change 4 constants:
```text
private static final String URL = "DB URL";
private static final String USERNAME = "YOUR USERNAME";
private static final String PASSWORD = "YOUR PASSWORD";
private static final String JDBC_DRIVER = "JDBC DRIVER";
```
 
5. Deploy the WAR file in Tomcat
6. Start the application