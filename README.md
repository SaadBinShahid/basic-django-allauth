# basic-django-allauth
Basic implementation of django-allauth.

doc: http://django-allauth.readthedocs.org/en/latest/index.html

- Django 1.7
- Python 2.7

#Err101 - Connection Refused
python -m smtpd -n -c DebuggingServer localhost:1025

Use this for a development debugging server.

settings.py

EMAIL_HOST = 'localhost'

EMAIL_PORT = 1025
