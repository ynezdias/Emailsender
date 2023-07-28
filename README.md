Django-Email-Sender
Send email from Gmail Id in Django using HTML Template

Pre-Requisites
Python 3.8
Pip
Git
Steps to run:
In PipFile, the dependencies are mentioned. It is recommended to run the app inside a virtual environment to avoid conflict of existing dependencies.

Run the command pip install pipenv

Run pipenv shell. Creates virtual env

Run pipenv install. Installs dependencies from the PipFile and creates PipFile.lock

Run python email_project/manage.py runserver to start the server

Open http://127.0.0.1:8000/api/send-mail to start

USE THE FOLLOWING STEPS

1.Create and activate a virtualenv (Python 3)
pipenv --python 3 shell

2.Install requirements
pipenv install

3.Create a MySQL database
CREATE DATABASE chat CHARACTER SET utf8;

4.Start Redis Server
redis-server

5.Init database
./manage.py migrate

6.Run tests
./manage.py test

7.Create admin user
./manage.py createsuperuser

8.Run development server
./manage.py runserver
