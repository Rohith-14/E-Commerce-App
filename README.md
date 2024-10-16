# E-Commerce Application

# Author
Rohith Neralla
## Introduction
This repository contains an e-commerce website project designed to offer a smooth and intuitive online shopping experience. Users can easily browse, search, and purchase products, while store owners can efficiently manage inventory, orders, and customers through the admin panel. Built with modern web technologies, the project is scalable and customizable, making it ideal for developers looking to create or enhance their own e-commerce platforms.

## Details
Clone the repository and open it in your preferred IDE (IntelliJ IDEA recommended).
Ensure the project is recognized as a Maven and Spring Boot project in IntelliJ. Adjust the working directory for Spring Boot to locate the views (web pages). Refer to IntelliJ’s Web Directories guide if needed.
Navigate to the JtProject directory.
Configure the database connection in the application.properties file.
Run the project by executing the main method in JtSpringProjectApplication.java.
Open http://localhost:8080/ in your browser.
If you’ve run the basedata.sql script on the database, log in as admin with admin/123, or manually create an admin user in the database.

## Database

You can use MySQL or MariaDB as the database for this project. Update the database connection settings in the application.properties file with the following properties:


db.url=jdbc:mysql://[db ip]:[db port]/ecommjava?createDatabaseIfNotExist=true
db.username=[your username]
db.password=[your password, if applicable]

If you encounter the error java.lang.IllegalArgumentException: Could not resolve placeholder 'db.driver', ensure the mysql-connector-java version in the pom.xml file matches your MySQL version and reload the Maven project.

After setting up the connection, populate the database by executing the basedata.sql script. Refer to relevant online resources for instructions based on the tool you’re using to access the database.
## Endpoints

http://localhost:8080/

http://localhost:8080/register

http://localhost:8080/admin/products

http://localhost:8080/admin/customers

http://localhost:8080/admin/categories

http://localhost:8080/admin/Dashboard
https://spring.io/guides/gs/serving-web-content
