# Useful Commands
This commands will be abit different on Linux and Mac OS

1. Activating your environment. Open project Directory and activate
`.\env-name\Scripts\activate`
2. Checking Django version in environment
`python -m django --version`
3. Creating a django project
`django-admin startproject mysite`
4. From terminal use `cd mysite` to move into the project directory
5. Running development server
`python manage.py runserver`
6. Creating django app
`python manage.py startapp polls`
7. Making migrations or adding fields to database
`python manage.py makemigrations`
8. After making migration, apply the migrations or create database with
`python manage.py migrate`
9. Type `python manage.py shell` to open django shell and `exit()` to quit
10. Creating Superuser
`python manage.py createsuperuser`


### Reference
## [Writing your first Django app](https://docs.djangoproject.com/en/3.1/intro/tutorial01/)
