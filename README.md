# watermelon-seller-form
This project is the simple multi-step form with django
Requirements
Python 3.8
1.First install venv package
2.sudo apt-get install python3-venv
3.create a virtual environment : python3 -m venv djangoenv
4.activate the virtual environment: source djangoenv/bin/activate
Basic Installation
5.Clone the repository: Using HTTPS
https://github.com/swathi-django/watermelon-seller-form.git
6.Usage
Install all packages using pip 
Package                Version
---------------------- --------
asgiref                3.6.0
Babel                  2.12.1
Django                 3.2.18
django-environ         0.10.0
django-money           3.1.0
django-widget-tweaks   1.4.12
mysql-connector-python 8.0.32
phonenumbers           8.13.7
Pillow                 9.4.0
pip                    22.0.2
protobuf               3.20.3
py-moneyed             2.0
PyMySQL                1.0.2
pytz                   2022.7.1
setuptools             67.5.1
six                    1.16.0
sqlparse               0.4.3
typing_extensions      4.5.0
Create tables in the DB by migrating:
python src/manage.py migrate
Create an admin user:
python src/manage.py createsuperuser
Start the developement server
python src/manage.py runserver
pages for dispalying data:
http://127.0.0.1:8000/ Multi-step for for seller giftcard survey
http://127.0.0.1:8000/results Display  giftcard info
