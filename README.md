django-polls-tutorial
=====================

A simple Django web application with custom models, views, automated tests, admin tools, etc. Created by following the resources available in [Django's documentation](https://docs.djangoproject.com/en/1.11/intro/).


Requirements
------------
* Python 3.4+
* Django 1.11+

Running
-------

(Optional) Create and activate a virtual environment.

```
virtualenv -p /usr/local/bin/python3 venv
source venv/bin/activate
```

Install project dependencies.

```
pip install -r requirements.txt
```

(Optional) Create an admin user to access the admin portal.

```
python manage.py createsuperuser
```

Run server.

```
python manage.py runserver
```

The server will load on `http://localhost:8000/polls/`. You can access the admin portal via `http://localhost:8000/admin/`

To exit the virtual environment:

```
deactivate
```


Testing
-------

The project was created using a test driven development strategy.

You don't need to launch an instance of the server to run the test cases. To run the test cases in `polls/tests.py`:

```
python manage.py test
```

To run tests on the command line:

```
python manage.py shell
```
