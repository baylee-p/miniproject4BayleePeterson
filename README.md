### INF601 - Advanced Programming in Python
### Baylee Peterson
### Mini Project 4


# Project Title

Following the Django tutorial, created a program that asks the users NFL questions.

## Description

I used the tutorial for Django to create a program that asks the users three questions and stores them in a database. 
The three questions consist of the users favorite team, coach, and quarterback. 

## Getting Started

### Dependencies

* asgiref==3.8.1
* Django==5.1.4
* django-debug-toolbar==4.4.6
* sqlparse==0.5.3


### Installing

* Download files from GitHub

### Executing program

* Open files from GitHub into PyCharm
* Be sure all files have uploaded to PyCharm correctly
* Enter the following code into the terminal
```
python manage.py makemigrations
```
* Next, enter the following code into the terminal
```
python manage.py migrate
```
* Next, enter the following code into the terminal and create an admin account
```
python manage.py createsuperuser
```
* Next, enter the following code into the terminal
```
python manage.py runserver
```
* Select the server link "http://127.0.0.1:8000/"

## Help

If you come across issues, be sure all files are properly downloaded and in PyCharm

## Authors

Baylee Peterson

## Version History

* 0.1
    * Initial Release

## Acknowledgments

https://docs.djangoproject.com/en/5.0/