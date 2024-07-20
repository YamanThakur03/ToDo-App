
# To-Do List Web Application

## Introduction

This is a web-based To-Do list application developed using the Django framework. The application helps users manage their tasks online, providing functionalities to add, view, edit, and delete tasks.

## Features

- **Add Task**: Create new tasks with a name and description.
- **View Tasks**: Display a list of all tasks.
- **Edit Task**: Update the details of existing tasks.
- **Delete Task**: Remove tasks that are no longer needed.
- **Task Completion**: Mark tasks as completed.

## Technologies Used

- **Django**: High-level Python web framework.
- **SQLite**: Lightweight, disk-based database.
- **HTML/CSS**: Front-end user interface.
- **Python**: Backend development language.

## Setup and Installation

1. **Clone the repository**:
    ```bash
    git clone "https://github.com/YamanThakur03/ToDo-App"
    cd todo_site
    ```

2. **Create a virtual environment**:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Apply migrations**:
    ```bash
    python manage.py migrate
    ```

5. **Run the development server**:
    ```bash
    python manage.py runserver
    ```

6. Open your web browser and navigate to `http://127.0.0.1:8000/`.

## Project Structure

- `manage.py`: Django's command-line utility for administrative tasks.
- `db.sqlite3`: SQLite database file.
- Application files:
  - Models, views, forms, and templates are organized under the `todo` directory.
  - Project configuration files are under the `todo_site` directory.

