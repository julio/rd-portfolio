## Setup
- $ `python3 -m venv venv`
- $ `source venv/bin/activate`
- $ `pip install -r requirements.txt`
- $ `pip install --upgrade pip`

## Create project
- $ `django-admin startproject personal_portfolio`
- $ `mv personal_portfolio/manage.py ./`
- $ `mv personal_portfolio/personal_portfolio/* personal_portfolio`
- $ `rm -r personal_portfolio/personal_portfolio/`

## Finish setup
- $ `python manage.py migrate projects
- $ `python manage.py migrate blog

## Admin page
- $ `python manage.py createsuperuser`

## Run dev
- $ `./manage.py runserver
