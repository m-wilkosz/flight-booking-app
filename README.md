# Flight Booking App
[![](https://skills.thijs.gg/icons?i=py,django,js,html,css,sqlite)](https://skills.thijs.gg)

### Description
This is a flight booking Django application written in Python, JavaScript, HTML and CSS.

### Features
- users can create their user account
- users can book both one-way as well as round-trip tickets
- pages are mobile responsive
- users can cancel their booked tickets
- users can view their previously booked tickets
- tickets are downloadable as pdf document
- as-you-type search

### Technologies
The project was created with:
- Python 3.9
- Django 3.1.2
- JavaScript ES6
- HTML 5
- CSS 3
- SQLite 3.38

### Setup
First, you have to install Python 3.9 and Django 3 if you don't already have them:
```
sudo apt-get install python3.9
sudo apt install python3-pip
python -m pip install Django
```
Then install project dependencies by running:
```
python -m pip install -r requirements.txt.
```
Make and apply migrations:
```
python manage.py makemigrations
python manage.py migrate
```
Create superuser:
```
python manage.py createsuperuser
```
Run the web server by this command:
```
python manage.py runserver
```
App is available at 127.0.0.1:8000.
