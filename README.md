# Todo List Web Application

This project is a web application for managing tasks and tags. Users can create, update, and delete tasks, as well as organize them using tags. The application provides a simple and intuitive interface for an efficient task management experience.

## Features

- Create, view, update, and delete tasks.
- Assign tags to tasks to categorize them.
- Mark tasks as completed or undo the completion status.
- Display tasks ordered by completion status (not done to done) and creation time (newest to oldest).
- Manage tags: create, view, update, and delete tags.

## Getting Started

### Prerequisites

- Python3
- Django
- Any additional dependencies specified in the `requirements.txt` file.

### Installation

   ```bash
   git clone https://github.com/niksgawrilenko/todo_list
   git checkout develop
   cd todo_list
   python -m venv venv #(On Windows)
   venv\Scripts\activate #On macOS and Linux
   source venv/bin/activate
   pip install -r requirements.txt
   python manage.py migrate
   python manage.py runserver
   ```





