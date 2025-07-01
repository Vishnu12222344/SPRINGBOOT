# 🌱 Spring Boot Demo Project

A simple Spring Boot application for demonstrating RESTful APIs and layered architecture.

## 🚀 Tech Stack

- Java 17
- Spring Boot
- Spring Web
- Spring Data JPA
- H2/MySQL/PostgreSQL (as per config)
- Maven
## 📁 Project Structure

| Path                                                   | Description                                      |
|--------------------------------------------------------|--------------------------------------------------|
| `demo_demo/`                                           | Root directory                                   |
| ├── `src/main/java/com/example/demo/`                  | Main Java source folder                          |
| ├── ├── `HomeController.java`                          | Home page or index controller                    |
| ├── ├── `SpringBootProjectApplication.java`            | Main class (entry point)                         |
| ├── ├── `User.java`                                    | POJO/entity class                                |
| ├── ├── `UserController.java`                          | REST controller for user operations              |
| ├── `src/main/resources/`                              | Resource files                                   |
| ├── ├── `static/`                                      | Static files (CSS/JS/images)                     |
| ├── ├── `templates/`                                   | Thymeleaf templates                              |
| ├── ├── `application.properties`                       | Application configuration                        |
| ├── `src/test/java/com/example/demo/`                  | JUnit test package                               |
| ├── ├── `SpringBootProjectApplicationTests.java`       | JUnit test class                                 |
| `pom.xml`                                              | Maven build configuration                        |
| `mvnw / mvnw.cmd`                                      | Maven wrapper scripts                            |



## 🧭 Code Navigation Guide

| File/Folder                      | Purpose                                       |
|----------------------------------|-----------------------------------------------|
| `HomeController.java`           | Handles base web routes (e.g., homepage)      |
| `UserController.java`           | Contains REST API endpoints for users         |
| `User.java`                     | Model class representing a User               |
| `application.properties`        | Configuration for server, DB, etc.            |
| `SpringBootProjectApplication`  | Main application entry point (`@SpringBootApplication`) |
| `static/`, `templates/`         | Frontend resources if using Thymeleaf         |
| `SpringBootProjectApplicationTests` | Test class for Spring context                |

## ▶️ How to Run the Application

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/demo_demo.git
   cd demo_demo
