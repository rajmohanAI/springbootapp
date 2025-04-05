<<<<<<< HEAD
# Spring Boot Web Application

This is a simple Spring Boot web application that includes a login screen and a home screen. The application demonstrates basic user authentication and displays a welcome message.

## Project Structure

```
spring-boot-web-app
├── src
│   ├── main
│   │   ├── java
│   │   │   └── com
│   │   │       └── example
│   │   │           └── springbootwebapp
│   │   │               ├── SpringBootWebAppApplication.java
│   │   │               ├── controller
│   │   │               │   ├── HomeController.java
│   │   │               │   └── LoginController.java
│   │   │               └── model
│   │   │                   └── User.java
│   │   ├── resources
│   │   │   ├── static
│   │   │   │   └── styles.css
│   │   │   ├── templates
│   │   │   │   ├── home.html
│   │   │   │   └── login.html
│   │   │   └── application.properties
│   └── test
│       └── java
│           └── com
│               └── example
│                   └── springbootwebapp
│                       └── SpringBootWebAppApplicationTests.java
├── mvnw
├── mvnw.cmd
├── pom.xml
└── README.md
```

## Getting Started

### Prerequisites

- Java Development Kit (JDK) 17 or higher
- Maven
- Visual Studio Code with the following extensions:
  - Java Extension Pack
  - Spring Boot Extension Pack

### Steps to Create and Run the Application

1. **Create Project Directory**: Open VS Code and create a new folder named `spring-boot-web-app`.
2. **Set Up Directory Structure**: Inside the folder, create the directory structure as specified above.
3. **Create Files**: Create the necessary Java and resource files, and copy the provided content into the respective files.
4. **Open Terminal**: Open a terminal in VS Code and navigate to the project directory.
5. **Run the Application**: Execute the command `./mvnw spring-boot:run` (or `mvnw.cmd spring-boot:run` on Windows) to start the application.
6. **Access the Application**: Open a web browser and go to `http://localhost:8080/login` to access the login page.
7. **Login**: Enter your username and password (authentication logic can be added later) and click the login button.
8. **Welcome Page**: After logging in, you will be redirected to the home page displaying "Welcome Dragon".

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
=======
# springbootapp
Web App created for springboot application
>>>>>>> 580559309d2d968ee36e022a1fbc5af30207de14
