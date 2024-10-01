
# Developed By Syntrilo - Rishabh Kumar

## Instructions: Make sure all the following are installed on your system:

- Install the requirements: pip install -r requirements.txt

Django==3.1.1
mysql-connector==2.2.9
virtualenv==20.0.31
dj-database-url==0.5.0
gunicorn==20.0.4
psycopg2==2.8.6
whitenoise==5.2.0
Pillow
requests

## After that Follow these steps:

- Make database migrations: python manage.py makemigrations
- Migrate the database: python manage.py migrate
- Finally, run the application: python manage.py runserver

## For Admin Login Credentials, please create one using superuser

- Create Admin Login: python manage.py createsuperuser



