# Django To-Do List App

A simple and user-friendly To-Do list application built with Django. This app allows users to register, log in, and manage their tasks with full CRUD (Create, Read, Update, Delete) functionality.

---

## Features

- **User Authentication**:
  - Register a new account.
  - Log in and log out securely.
- **Task Management**:
  - Create new tasks with a title and description.
  - Mark tasks as complete or incomplete.
  - Update existing tasks.
  - Delete tasks.
- **Search Functionality**:
  - Search for tasks by title.
- **Responsive Design**:
  - Clean and modern user interface.

---

## Technologies Used

- **Backend**: Django (Python)
- **Frontend**: HTML, CSS
- **Database**: SQLite (default Django database)

---

## Setup Instructions

Follow these steps to set up and run the project locally.

### Prerequisites

- Python 3.x
- Pip (Python package manager)

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/latifakhair/django-todolist-app.git
   cd django-todolist-app

2. **Create a virtual environment (optional but recommended):**:
     python -m venv venv
     source venv/bin/activate  # On Windows: venv\Scripts\activate

3. **Install dependencies**:
pip install -r requirements.txt

4. **Run migrations**:
python manage.py migrate

5.**Create a superuser (optional, for accessing the Django admin panel)**:
python manage.py createsuperuser

6. **Start the development server**:
python manage.py runserver

7.**Access the app**:
Open your browser and go to http://127.0.0.1:8000/.
Register a new account or log in if you already have one.

Acknowledgments
Inspired by various To-Do list apps.
Built with Django, one of the most popular Python web frameworks.