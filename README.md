# todo-list-django

A simple and efficient API for basic CRUD operations on a to-do list, built with Django REST Framework. It includes a responsive frontend using Bootstrap and CSS, with API calls made via vanilla JavaScript.

## Features
- Task Management: Easily create, view, update, and delete tasks.
- Responsive Design: User-friendly interface that adapts to various devices and screen sizes.
- Django REST Framework: Robust backend for managing API endpoints.
- Bootstrap Integration: Clean and modern UI components.
- Vanilla JavaScript: Simple and efficient API calls without the need for heavy frameworks.
- SQLite Database: Lightweight and easy-to-use database for local development.

## API Endpoints

##### 1. API Overview

- Endpoint: POST /api/
- Description: Displays an overview of the API's urls.

##### 2. Create task

- Endpoint: POST /api/task-create/
- Description: Creates a new task.

##### 3. Retrieve tasks

- Endpoint: GET /api/task-list/
- Description: Retrieves a list of all tasks.

##### 4. Retrieve task

- Endpoint: GET /api/task-detail/{id}/
- Description: Retrieves a specific task.

##### 5. Update task

- Endpoint: PUT /api/task-update/{id}/
- Description: Updates an existing task.

##### 6. Delete task

- Endpoint: DELETE /api/task-delete/{id}/
- Description: deletes a task.

## Contributing
Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (git checkout -b feature/your-feature-name).
3. Make and commit your changes (git commit -m 'Add some feature').
4. Push to the branch (git push origin feature/your-feature-name).
5. Open a pull request.
