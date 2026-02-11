Project Title

Task Management REST API

📖 Description

A backend RESTful API built using Django REST Framework that allows users to manage personal tasks with JWT authentication, filtering, ordering, and pagination.

🚀 Features

User authentication using JWT

Create, update, delete, and view tasks

Each user can access only their own tasks

Filter by status and priority

Order by created date and due date

Pagination support

🛠 Tech Stack

Python

Django

Django REST Framework

Simple JWT

SQLite (default DB)

⚙️ Installation
git clone <your-repo-url>
cd todo_api
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver

🔐 Authentication
POST /api/token/
POST /api/token/refresh/

📌 Endpoints
GET    /api/tasks/
POST   /api/tasks/
PUT    /api/tasks/{id}/
DELETE /api/tasks/{id}/
