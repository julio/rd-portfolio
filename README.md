## Setup
- $ `python3 -m venv venv`
- $ `source venv/bin/activate`
- $ `pip install -r requirements.txt`
- $ `pip install --upgrade pip`

## Finish setup
- $ `./manage.py migrate`
- $ `./manage.py migrate projects`
- $ `./manage.py migrate blog`

## Admin page
- $ `python manage.py createsuperuser`

## Run dev
- $ `./manage.py runserver`
