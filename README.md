# Django-Ecommerce

Ecommerce website built with Django 2.2.3, Python 3.7.3, and bootstrap 4.



# Installation

`git clone https://github.com/T33C33/S3-ecommerce`

`cd Django-Ecommerce`

`pip install virtualenv`

`virtualenv env`

# For Mac/ Linux

`source env/bin/activate`

# For Window

`env\Scripts\activate`

`pip install -r requirements.txt`

Install below version in terminal and 'New Version will face version conflict error'

```python

pip install Django==2.2.4
python -m pip install django-allauth==0.40.0
pip install django-crispy-forms==1.7.2
pip install django-countries==5.5
pip install stripe==2.37.1
pip install Pillow

```

`python manage.py makemigrations`

`python manage.py migrate`

`python manage.py runserver`

# For Admin Login

```python
python manage.py createsuperuser
Username : admin
Password : 12345678
```



