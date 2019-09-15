## Setup
- $ `python3 -m venv venv`
- $ `source venv/bin/activate`
- $ `pip install -r requirements.txt`
- $ `pip install --upgrade pip`

## Finish setup
- $ `python manage.py migrate`
- $ `python manage.py migrate projects`
- $ `python manage.py migrate blog`

## Admin page
- $ `python manage.py createsuperuser`

## Run dev
- $ `./manage.py runserver`
