# Packages

django
python-dotenv 0.21.0
djangorestframework==3.14.0
pytest==7.4.3
pytest-django-4.7.0
black==23.11.0
flake8-6.1.0

# Commands

django-admin startproject drfecommerce

./manage.py runserver

from django.core.management.utils import get_random_secret_key
print(get_random_secret_key())

pip install --upgrade pip

pip freeze > requirements.txt


## Pytest

pytest -h # prints options _and_ config file settings

## VS Code Extensions

Python (Microsoft)
Night Owl (sarah.drasner) # vs code theme
SQLite (alexcvzz)
Black Formatter (Microsoft)
Flake8 (Microsoft)
