## Setup
- $ `python3 -m venv venv`
- $ `source venv/bin/activate`
- $ `pip install Django`
- $ `pip install --upgrade pip`

## Create project
- $ `django-admin startproject personal_portfolio`
- $ `mv personal_portfolio/manage.py ./`
- $ `mv personal_portfolio/personal_portfolio/* personal_portfolio`
- $ `rm -r personal_portfolio/personal_portfolio/`

## Finish setup
- $ `python manage.py runserver`
- $ `python manage.py migrate projects`
