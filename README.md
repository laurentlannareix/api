# Set up

1 - Add .env file in the root of your project (This is where your settings.py file is located)

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
conda install requirements.txt 
```
