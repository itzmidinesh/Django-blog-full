# django-blog-full

## Overview
This is my attempt at building a blog website using Django to resharpen my skills again. This is just an application with minimum styling with Bootstrap & CSS. The functionality is full with login, logout, register, post view, post detail view, post by user view, profile, etc.

### Setup

The first thing to do is to clone the repository:

```sh
$ git clone https://github.com/itzmidinesh/django-blog-full.git
$ cd django-blog-full
```
---
Create a virtual environment to install dependencies in and activate it:

```sh
$ virtualenv venv
$ venv/Scripts/activate
```
---
Install project dependencies:

```sh
(venv)$ pip install -r requirements.txt
```
Note the `(venv)` in front of the prompt. This indicates that this terminal session operates in a virtual environment set up by `virtualenv`.

---
Once `pip` has finished installing the dependencies, apply the migrations and run the development server:
```sh
(venv)$ cd blog
(venv)$ python manage.py migrate
(venv)$ python manage.py runserver
```
And navigate to `http://127.0.0.1:8000/articles/`

---
If you want to use the admin page, create a superuser:
```sh
(env)$ python manage.py createsuperuser
```
And navigate to `http://127.0.0.1:8000/admin/`

---
You can register from the Navigation bar at the top of the page and add posts as well.