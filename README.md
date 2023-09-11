# SpringBootTaskTrackerProject
# Spring Boot Task Tracer

Spring Boot Task Tracer is a simple web application designed to help you manage your tasks and to-dos. This application is built using the Spring Boot framework and provides basic CRUD (Create, Read, Update, Delete) operations for managing tasks.

## Introduction

Spring Boot Task Tracer allows you to:

- View a list of all your tasks.
- Add new tasks.
- Update existing tasks.
- Delete tasks.

This README provides an overview of the application's structure and key components.

## Getting Started

### Prerequisites

Before you begin, ensure you have met the following requirements:

- Java Development Kit (JDK) 8 or higher installed on your system.
- A Java IDE (e.g., IntelliJ IDEA, Eclipse) for development.
- Maven for building and managing dependencies.

### Clone the Repository

To get started, clone this repository to your local machine:

```bash
git clone <repository_url>
```

### Build and Run

1. Open the project in your Java IDE.
2. Build the project using Maven.
3. Run the application.

By default, the application runs on `localhost:8080`.

## Usage

### Overview

The core of the application is divided into three main components:

1. **TodoController:** This class handles HTTP requests and interacts with the service layer to perform CRUD operations on tasks.

2. **TodoService:** The service layer contains business logic for task management. It uses an in-memory list to store tasks, simulating a database.

3. **TodoRepository:** This interface extends JpaRepository to provide basic database operations for the `Todo` entity. However, in this application, an in-memory list is used instead of a database.

### Endpoints

- `/list-todos`: Displays a list of all tasks.
- `/add-todo` (GET): Shows a form to add a new task.
- `/add-todo` (POST): Handles the submission of a new task.
- `/delete-todo`: Deletes a task based on the provided `id`.
- `/update-todo` (GET): Shows a form to update an existing task.
- `/update-todo` (POST): Handles the submission of updated task details.

### Data Model

The `Todo` class represents a task with the following attributes:

- `id`: Unique identifier for the task.
- `username`: Username associated with the task.
- `description`: Task description.
- `targetDate`: Target date for completing the task.
- `done`: Boolean indicating whether the task is completed.

### Security

This application does not include authentication or authorization. It is recommended to add security features if deploying it in a production environment.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and test them thoroughly.
4. Create a pull request with a clear description of your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
