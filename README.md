## django-blog project 

###
##### Inspired by: 
[Antonio Melé's Django 3 by Example, Packt Pub 
](https://www.packtpub.com/eu/web-development/django-3-by-example-third-edition)
##


##### Requirements
- Python >= 3.6 virtualenv
- PostgreSQL >= 9.5


###
##### To run locally, it's recommended to do as follows:

####
- Install dependencies:
```
pip install -r requirements.txt
``` 

####
- Create .env file using .env.example file

####
- Fill .env file variables

####
- Make Migrations from existing Models:
```
python src/manage.py makemigrations
```        

####
- Run Migrations:
```
python src/manage.py migrate
```
    
####
- Create a Superuser:
```
python src/manage.py createsuperuser
```
    
####
- Run project on localhost:
```
python src/manage.py runserver
```
    
####
- Change Database Settings in settings.py if necessary