# POC: Docker + Django

## Workstation Setup

```sh
python3 -m venv venv
python -m pip install Django
python -m django --version
```

##

```sh
django-admin startproject mysite
cd mysite
python manage.py runserver
python manage.py startapp polls
python manage.py runserver
```

## Guides

- https://docs.djangoproject.com/en/4.0/intro/tutorial01/
