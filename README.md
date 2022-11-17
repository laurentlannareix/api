# Getting started

This project is made to helps you create an authentication page based on Auth0 and Django backend.

## Requirements

    * Anaconda environment installed

## Installation

1 - Add .env file into the app root - this is where the settings.py file is located.

2 - Then, add the following environment variables into the .env file :


```
SECRET_KEY=YOUR_SECRET_KEY

AUTH0_DOMAIN=YOUR_AUTH0_DOMAIN
AUTH0_CLIENT_ID=YOUR_AUTH0_CLIENT_ID
AUTH0_CLIENT_SECRET=YOUR_AUTH0_CLIENT_SECRET
```

Notes :
Auth0 IDs are from your Auth0 dashbord App settings

You can generate a secret_key with Djecrety

3 - Install requirements :

```
cd api
conda install pip
pip install requirements.txt 
```

Note : install pip if you use conda environment

4 - Migrate your django models :
```
python manage.py migrate
```

5 - Run server :
```
python manage.py runserver
```

6 - After clicking on this link from your terminal http://127.0.0.1:8000/, You should see this home page : 

![alt text](https://github.com/laurentlannareix/api/blob/d8b3304df238ff981d63c9916c390c031f831306/img/home.png)

7 - Auth0 allows you to login : 

![alt text](https://github.com/laurentlannareix/api/blob/96ade99a6fd5cdb6196db47265a32599ff7f8ac6/img/login.png | width=200 height=300)

Notes : The login / sign in page is fully configurable into your Auth0 dashboard App :  https://auth0.com/