# Readme

This page documents the process for following along with the django 201 course on skillshare.

### setup our virtual environment

`pipenv install django`

Enter the virtual environment:

`pipenv shell`

### Setup our Django project

`django-admin startproject til`

`python3 manage.py migrate`

### Setup git 

When setting up git, one thing we do not want to do is add the sqlite database to git.

`git init`

`wget https://github.com/KalobTaulien/django-201/blob/main/.gitignore`

This will contain a bunch of stuff to be ignored when we try and upload to our git repo