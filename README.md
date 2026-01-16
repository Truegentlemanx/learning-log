# Learning Log

A simple Django app for tracking what you are learning. Users can register, create topics, and add entries under each topic.

## Features
- User accounts with login and registration
- Create, view, and manage personal learning topics
- Add and edit entries for each topic
- Access control so users only see their own data

## Tech Stack
- Python 3.14.2
- Django 5.2
- SQLite (default)
- django-bootstrap5

## Quick Start
1. Create and activate a virtual environment.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run migrations:
   ```bash
   python manage.py migrate
   ```
4. Start the dev server:
   ```bash
   python manage.py runserver
   ```
5. Open `http://127.0.0.1:8000/` and register a user.

## Configuration
Environment variables:
- `DJANGO_DEBUG`: set to `False` to disable debug mode (defaults to True otherwise).

## Deployment
For a production setup, see `requirements_remote.txt` for additional packages (e.g., Gunicorn, PostgreSQL driver).
