# springBoot-CRUD

This application is a simple CRUD (Create, Read, Update, Delete) application built using Spring Boot and JPA (Java Persistence API). It allows a user to perform CRUD operations on a database through a simple web interface.

## Requirements
- Java 11 or higher
- Maven 3.6.3 or higher
- A database management system such as MySQL, PostgreSQL, or Oracle

## Getting Started
1. Clone the repository: git clone https://github.com/saeedmaldosary/springBoot-CRUD.git
2. Navigate to the project directory: cd springBoot-CRUD
3. Build the project: mvn clean install
4. Run the application: mvn spring-boot:run
5. Access the web interface at http://localhost:3000

## Configuration
The application can be configured by modifying the application.properties file located in the src/main/resources directory. You can set the following properties:

- `spring.datasource.url`: the JDBC URL of the database
- `spring.datasource.username`: the username for the database
- `spring.datasource.password`: the password for the database
- `spring.jpa.hibernate.ddl-auto`: the type of database initialization. Set to `create-drop` to drop and recreate the database on each application run, or `update` to update the database schema if necessary.

## Deployment
To deploy the application, you can build a jar file by running mvn clean package. The jar file will be located in the target directory and can be run using the java -jar command.

You can also use a tool like Docker to build and run a containerized version of the application.
