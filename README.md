# Django_CRUD
 Django application that performs CRUD operations

## Install Required Packages

The Django CRUD project only need a single Python package "Django", it was built and tested with Django 3.x version. 
To install it use the following command:
```
pip install -r requirements.txt
```
Django 3 requires Python 3, if you need help setting up Python 3 on your machine 
you can consult DigitalOcean great documentation on [How To Install and Set Up a Local Programming Environment for Python 3](https://www.digitalocean.com/community/tutorial_series/how-to-install-and-set-up-a-local-programming-environment-for-python-3)

## Running the Application

Before running the application we need to create the needed DB tables:
```
./manage.py migrate
```
Now you can run the development web server:
```
./manage.py runserver
```
To access the applications go to the URL http://localhost:8000/
## I need a user and password to access crud
Yes, the application demonstrate how CRUD can work with Django users, and you do
need to create a user to test it, you can create a user using the following command:

    ./manage.py createsuperuser

To create a normal user (non super user), you must login to the admin page and
create it: <http://localhost:8000/admin/>
