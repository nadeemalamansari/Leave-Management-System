# 🗓️ Leave Management System - Django

A web-based Leave Management System built using Django. This application streamlines the process of requesting, approving, and managing leaves for employees, managers, and administrators.

## 🚀 Features

- Employee registration and login
- Leave application form with type, date range, and reason
- Manager dashboard to approve/reject leave requests
- Admin panel for managing users and leave types
- Role-based access control (Admin, Manager, Employee)
- Leave history and status tracking
- Responsive Bootstrap UI

## 📸 Screenshots

| Login Page | Employee Dashboard | Admin Panel |
|------------|--------------------|-------------|
| ![image](https://github.com/user-attachments/assets/8fa7dde5-0429-4439-b415-92c46399960d)
 | ![image](https://github.com/user-attachments/assets/b71d53a2-7b08-4e06-b527-ed0e0fe849e1)


## 🛠️ Technologies Used

- **Backend:** Python, Django
- **Frontend:** HTML, CSS, Bootstrap, JavaScript
- **Database:** SQLite (default), can be switched to MySQL/PostgreSQL
- **Tools:** VS Code, Git

## 🧱 Project Structure
leave-management-system/
├── manage.py
├── lms/ # Django project config
├── users/ # Custom user models and auth
├── leaves/ # Leave-related models and views
├── templates/ # HTML templates
├── static/ # CSS/JS/Images
└── db.sqlite3 # Default database

## ⚙️ Setup Instructions

1. **Clone the repository**
```bash
gh repo clone nadeemalamansari/Leave-Management-System

python -m venv venv
source venv/bin/activate    # On Windows: venv\Scripts\activate
pip install -r requirements.txt
Create a virtual environment and activate it

```bash
python -m venv venv
source venv/bin/activate    # On Windows: venv\Scripts\activate
Install required dependencies

```bash

pip install -r requirements.txt
Apply database migrations

```bash

python manage.py makemigrations
python manage.py migrate
Create superuser (optional but recommended)

```bash

python manage.py createsuperuser
Run the development server

```bash
python manage.py runserver
Open in browser
Go to http://127.0.0.1:8000/ to access the application.
