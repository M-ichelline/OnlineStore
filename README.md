# OnlineStore
A Spring Boot Backend for an online store, providing APIs for product management, users, order and secure e-commerce operations

# Technology used

Java
Spring Boot
Spring Web
Spring Data JPA
Spring Security
Hibernate
PostgreSQL
Maven
Swagger / OpenAPI
Git & GitHub


#Requirements

Before running the project, make sure you have:
Java 17 or later
Maven
PostgreSQL
Git


#Installation

1. Clone the repository
git clone https://github.com/YOUR-USERNAME/online-store.git

3. Navigate to the project
cd online-store

4. Configure the database
Create a PostgreSQL database and update your database configuration in:

src/main/resources/application.properties

Example:

spring.datasource.url=jdbc:postgresql://localhost:5432/online_store
spring.datasource.username=your_username
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true


4. Run the application

Using Maven:

mvn spring-boot:run



