# Book Library Project

## Overview

The Book Library Project is a web application that allows users to manage a collection of books. The frontend is built using Angular, while the backend is powered by Spring Boot. The application supports basic CRUD (Create, Read, Update, Delete) operations for books, user authentication, and a simple user interface to interact with the library.

## Features

- User Authentication: Register, login, and manage user sessions.
- Book Management: Add, edit, view, and delete books.
- Search Functionality: Search for books by title or author.
- Responsive Design: User-friendly interface accessible on various devices.

## Technologies Used

### Frontend
- [Angular](https://angular.io/)
- HTML5
- CSS3
- TypeScript
- Bootstrap

### Backend
- [Spring Boot](https://spring.io/projects/spring-boot)
- Java
- Spring Security
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

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/book-library.git
    cd book-library
    ```

2. **Backend Setup:**

    - Navigate to the backend directory:
      ```bash
      cd backend
      ```
    - Update the `application.properties` file with your MySQL database configuration:
      ```properties
      spring.datasource.url=jdbc:mysql://localhost:3306/booklibrary
      spring.datasource.username=yourusername
      spring.datasource.password=yourpassword
      spring.jpa.hibernate.ddl-auto=update
      ```
    - Build and run the Spring Boot application:
      ```bash
      mvn clean install
      mvn spring-boot:run
      ```

3. **Frontend Setup:**

    - Navigate to the frontend directory:
      ```bash
      cd frontend
      ```
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

## Project Structure

```
book-library/
│
├── backend/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   │   └── com/
│   │   │   │       └── example/
│   │   │   │           └── booklibrary/
│   │   │   ├── resources/
│   │   │       └── application.properties
│   │   └── test/
│   └── pom.xml
│
├── frontend/
│   ├── src/
│   │   ├── app/
│   │   ├── assets/
│   │   ├── environments/
│   │   └── index.html
│   └── angular.json
│
└── README.md
```

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature/your-feature-name`).
6. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

If you have any questions or feedback, feel free to reach out:

- Author: Kanyanta Pythias
- Email: kanyantapythias072@gmail.com

---

Thank you for using the Book Library Project! We hope it helps you manage your book collection effectively. Happy reading!
