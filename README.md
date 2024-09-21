# Django Blog App

A Django web application where users can register, log in, log out, and add blogs that other users can see. This project serves as a simple blogging platform with user authentication and authorization.

## Features

- User registration, login, and logout.
- Create, view, and manage blog posts.
- Authenticated users can create blogs, while other users can view them.

## Requirements

- Python 3.10+
- Django 4.1+
- Virtualenv (recommended)

## Setup and Installation

### 1. Clone the Repository

```bash
git clone https://github.com/umerkhayyam91/Django_Blog_App.git
cd dummyproject


Steps:
1. Create and Activate Virtual Environment
python -m venv venv
source venv/bin/activate    # On Windows use: venv\Scripts\activate

2. Run Migrations
python manage.py migrate

3. Create Superuser (Optional)
python manage.py createsuperuser

4. Run the Development Server
python manage.py runserver
