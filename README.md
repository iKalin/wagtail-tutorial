# wagtail-tutorial
Wagtail project tutorial from their docs


## Prerequisites

- pip (version 9.x)
- virtualenv (version 15.x)


## Installation

```
git clone git@github.com:robasaad/wagtail-tutorial.git
cd wagtail-tutorial
virtualenv venv
source venv/bin/activate
```


## Build

```
pip install -r requirements.txt
```


## Run

Go to the /mysite/ app directory and type in:

```
python manage.py runserver
```

and then go to http://localhost:8000 in your browser


## Stop

Stop the virtual environment by typing in:

```
deactivate
```


## Admin

Access the admin panel by going to /admin/


## CMS

Go to /cms/ to access Wagtail. Same credentials as the admin (if you're not logged in).
