# Spring BootTask Tracker BACKEND API

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

- `id`: Unique identifier for the task.

  
- `username`: Username associated with the task.

- `description`: Task description.
  
- `targetDate`: Target date for completing the task.

  
- `done`: Boolean indicating whether the task is completed.


### Security

This application does have authentication or authorization IMPLEMENTED USING SPRING SECURITY. 
