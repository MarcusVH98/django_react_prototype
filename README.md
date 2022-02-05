# django_react_prototype

## Setup

#### Setup virtual environment:
`python -m venv .venv`

#### Install necessary packages:
Backend packages:
`pip install django djangorestframework django-cors-headers`

Frontend packages:
>Note: try to use react-bootstrap bootstrap@5.1.3 instead of reactstrap
`npm install bootstrap reactstrap axios --save`

#### Creating a local database:
`MySql`
`CREATE DATABASE testdb`

## How to run
Start backend:
`cd django_react_proj` (Not needed when project structure is fixed)
`python manage.py runserver`

Start frontend:
`cd students-fe`
`npm start`

![page-screenshot](page-screenshot.png)
