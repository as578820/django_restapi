# django_restapi

Install Python and pip by using official docs.

git clone https://github.com/as578820/django_restapi.git
cd django_restapi
pip install -r requirements.txt

check db configuration in djangoproject/settings.py file [DATABASE section] and change by your db details

run django.sh

open below url:
http://127.0.0.1:8000/users/create
apply POST method, add name and email
sample input:
{
    "name": "john doe",
    "email": "john@doe.com"
}

apply GET method by below URL:
http://127.0.0.1:8000/users/read/<id> e.g.1,2,3 etc.

apply PUT method by below URL:
http://127.0.0.1:8000/users/update/<id> e.g.1,2,3 etc. 

apply delete method by below URL:
http://127.0.0.1:8000/users/delete/<id> e.g.1,2,3 etc. 
