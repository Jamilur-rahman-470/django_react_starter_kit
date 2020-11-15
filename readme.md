# Django React Starter Kit

Django react starter kit a django app configured to work with react as front end. The app uses parcel.js to compile react. This is base starter so you don't have to configure react to work with django. 

The djnago app exposes a rest api to communicate with react frontend. 


## Running the app
1. create a virtual environment with what ever you prefeer.
2. install requirements with 


```bash
    pip install requirements.txt
```

3. cd into front and install js dependencies
```bash
    cd front
    
    yarn install 
    
    or

    npm install
```

```bash
    npm run develop
```
to watch on changes in react

```bash
    npm run build 
```
to make a production build


```bash
    python manage.py runserver
```

on root directory to run django
