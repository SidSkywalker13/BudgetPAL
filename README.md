# BudgetPAL - Your one and only Expense Tracker App!

Welcome to the BudgetPAL repository! It's a simple, yet elegant web application that allows users to manage and track their expenses. Pretty simple, right? 

## Demo Video

Check this one out to see how it's done!
[Expense Tracker Demo](https://youtu.be/IlUs0ESfFK4)

## Features

You can:

- Add, update, and delete expenses!
- View expense summaries in a table and gain insights on the total amount spent!
- Filter expenses by year, month, and type of expense! Pretty cool!
- Did I mention there's pagination? Sure is!
- Customize your expense categories!
- Download expenses as CSV files!
- Oh yes, it's designed to be responsive! 

## What runs this thing?

- Java 17.0
- Spring Boot 3
- Spring Data JPA (for data access)
- Thymeleaf (for server-side templating)
- MySQL (as the database)
- Maven (for build and dependency management)
- HTML, CSS, Bootstrap
- The server is Tomcat, a built-in server of Spring Boot.

## Well, how do I start?

1. Clone the repository to your local machine!
2. Open the project in your preferred Java IDE.
3. Make sure you have MySQL installed on your machine!
4. Create a MySQL database named `budgetpal` or update the database configuration in `src/main/resources/application.properties` with your database settings.
6. Build and run the application using Maven via the `mvn spring-boot:run` command or via the IDE.
7. Access the app in your browser at `http://localhost:9191`! You can change the server port in the application.properties file if you'd like!



