# Ecommerce-website

Some technical information:
Django - 3.1.1
Django Allauth - 0.42.0
Django Crispy Forms - 1.9.2
Django Environ - 0.4.5
Stripe - 2.51.0
To Install:
Cloning the Repository:

$ cd django_ecommerce 

Installing the environment control:

$ pip install virtualenv

$ virtualenv env

Activating the environment:

on Windows:

env\Scripts\activate

on Mac OS / Linux:

$ source env/bin/activate

Installing dependencies:

$ pip install -r requirements.txt

Create a .env file on ecom folder (/ecom/.env) setting all requirements without using space after "=".

Copy and paste on our .env file:

DEBUG=
SECRET_KEY=
DEFAULT_FROM_EMAIL=
NOTIFY_EMAIL=
PAYPAL_SANDBOX_CLIENT_ID=
PAYPAL_SANDBOX_SECRET_KEY=
PAYPAL_LIVE_CLIENT_ID=
PAYPAL_LIVE_SECRET_KEY=
STRIPE_PUBLIC_KEY=
STRIPE_SECRET_KEY=
STRIPE_WEBHOOK_SECRET=

Last commands to start:

$ python manage.py makemigrations

$ python manage.py migrate

Create a super user:

$ python manage.py createsuperuser admin-name

Finishing running server:

$ python manage.py runserver
