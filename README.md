# Market place - electronics store

## Goal
The main aim of the project is to represent an online platform for sale with quick and understandable requests.

## Description
**“auth_”** application represents requests related to user authentication.

 **“core”** includes basic models, queries that form the basis of an online store. 

**“market”** consists of goods with certain characteristics, properties complementary to the product, as well as the integration of the user directly with the system by giving feedback.

**“payments”** application speaks for itself, it provides endpoints that help to order the delivery of a certain item.

It’s also used popular packages that put together a framework for the entire application.

## Virtual env
````
```
pip install virtualenvwrapper
mkvirtualenv yourOptinallyEnvironmentName
workon yourOptinallyEnvironmentName
pip install -r requirements.txt
```
````

## Run
````
```
python manage.py makemigrations
python manage.my migrate
python manage.py runserver
```
````
