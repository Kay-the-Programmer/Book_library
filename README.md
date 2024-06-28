# Book Library Project

## Overview

The Book Library Project is a web application that allows users to manage a collection of books. The frontend is built using Angular, while the backend is powered by Spring Boot. The application supports basic CRUD (Create, Read, Update, Delete) operations for books and a simple user interface to interact with the library.

## Features

- Book Management: Add, edit, view, and delete books.


## Technologies Used

### Frontend
- [Angular](https://angular.io/)
- HTML5
- CSS3
- TypeScript
- Bootstrap
- Material UI

### Backend
- [Spring Boot](https://spring.io/projects/spring-boot)
- Java
- Hibernate
- MySQL

## Getting Started

### Prerequisites

- Node.js and npm installed
- Angular CLI installed
- Java Development Kit (JDK) 17 installed
- Gradle installed
- MySQL database setup

### Installation

1. **Download backend zip folder:**
   
2. **Database Setup**
    - Create MySQL database
      ```bash
      CREATE DATABASE book_library;
      ```
3. **Backend Setup:**

    - Navigate to the backend directory:
      ```bash
      cd src/main/resources
      ```
    - Update the `application.properties` file with your MySQL database configuration:
      ```properties
      spring.datasource.url=jdbc:mysql://localhost:3306/book_library
      spring.datasource.username=yourusername
      spring.datasource.password=yourpassword
      spring.jpa.hibernate.ddl-auto=update
      ```
    - Build and run the Spring Boot application:
      ```bash
      ./gradlew build
      ./gradlew bootRun
      ```

3. **Frontend Setup:**

    - Download the fronted zip folder and extract:
    - Open project folder in preferred IDE preferrably Webstorm or VS Code text editor.
      
    - Install the dependencies:
      ```bash
      npm install
      ```
    - Run the Angular application:
      ```bash
      ng serve
      ```

4. **Access the Application:**

    Open your web browser and navigate to `http://localhost:4200`.


## Challenges
During this project the major problem that was encountered was the deprecation of some features and dependencies that I've been using.
Therefore it took time to understand and put up with the new features and make good use of them.


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact


- Author: Kanyanta Pythias
- Email: kanyantapythias072@gmail.com

---

