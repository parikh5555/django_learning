# django_learning

pip install django

pip install djangorestframework

pip install django-cors-headers

django-admin startproject DjangoAPI # Name of project DjangoAPI

python manage.py runserver #start dhango server

python manage.py startapp EmployeeApp # Creates EmployeeApp named app in DjangoAPI project

Setup Database

pip install jongo

pip install dsnpython

In settings.py 

DATABASES = {
    'default': {
        'ENGINE': 'djongo',
        'CLIENT': {
            "host":"mongodb://localhost:27017/"
            ,"name":"mytestdb"
        }
    }
}

# Then run 

python manage.py makemigrations EmployeeApp # Check migrations folder and file for correctness of schema

python manage.py migrate EmployeeApp
