# django_poll_application

It is a simple poll application using django

# Installing

Open terminal where you want to clone this project.

Clone the repo

git clone https://github.com/jobayer-rahman/django_poll_application.git

Create Python virtual env

## python3 -m venv venv

Activate virtual env

source venv/bin/activate

Upgrade pip

pip install --upgrade pip

Install dependencies from requirements.txt

pip install -r requirements.txt

Go to pollstar directory

cd pollstar

Migrate the database

python manage.py migrate

Create Super User. After giving this command it will prompt for username, password, email etc. Give this as you want.

python manage.py createsuperuser

Start the development server

python manage.py runserver

Open this link http://127.0.0.1:8000/ on your browser. 
