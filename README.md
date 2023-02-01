# django_poll_application
It is a simple poll application using django

# Installing

Open terminal where you want to clone this project.

Clone the repo

__git clone https://github.com/jobayer-rahman/django_poll_application.git__

Create Python virtual env

__python3 -m venv venv__

Activate virtual env

__source venv/bin/activate__

Upgrade pip

__pip install --upgrade pip__

Install dependencies from requirements.txt

__pip install -r requirements.txt__

Go to pollstar directory

__cd pollstar__

Migrate the database

__python manage.py migrate__

Create Super User. After giving this command it will prompt for username, password, email etc. Give this as you want.

__python manage.py createsuperuser__

Start the development server

__python manage.py runserver__

Open this link http://127.0.0.1:8000/ on your browser. 
