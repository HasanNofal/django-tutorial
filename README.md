# Description
This is a basic poll application that lets users view polls and vote on them
## Requirements
- Python 3
- Django 4
## Install
1- create python enviroment
```
python -m venv env
```
2- activate enviroment
```
. env/bin/activate
```
3- install requirements
```
pip install -r requirements.txt
```
## Usage
1- Run the following command:
```
python manage.py migrate
```
2- Create an admin user
```
python manage.py createsuperuser
```
3- Start the development server
```
python manage.py runserver
```
4- Open a web browser and go to:
```
http://127.0.0.1:8000/admin/
```
5- Login and create a new question  
6- Go to and click on your question:
```
http://127.0.0.1:8000/polls/
```
7- Make a vote and view the result