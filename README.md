# SpringBootTaskTrackerProject BACKEND API
# Spring Boot Task Tracer


![todoapi](https://github.com/JoseSagwe/SpringBootTaskTrackerProject/assets/110198843/ed30966d-348e-452a-9207-20980effe1c8)


Spring Boot Task Tracer is a simple web application designed to help you manage your tasks and to-dos. This application is built using the Spring Boot framework and provides basic CRUD (Create, Read, Update, Delete) operations for managing tasks.

## Introduction

Spring Boot Task Tracer APIS allows you to:

- View a list of all your tasks.
- Add new tasks.
- Update existing tasks.
- Delete tasks.

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
