# Personal Portfolio

A Simple Portfolio app build with Django.


# Running the Project Locally

## First, clone the repository to your local machine :

```bash
git clone https://github.com/Sakthivel203/portfolio-django-project.git
```

## Create a virtual environment :

```bash
$ python -m venv .venv
```

## Activate the virtual environment on Windows :

```bash
$ source venv/Scripts/activate
```

## To install Django :

```bash
$ pip install django
```

## For Database setup :

```bash
$ python manage.py makemigrations
```

## Apply the migrations :

```bash
$ python manage.py migrate
```

## To create an superuser account, use this command :

```bash
$ python manage.py createsuperuser
```

## Finally, run the development server :

```bash
$ python manage.py runserver
```