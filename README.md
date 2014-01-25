django-project-structure
========================

What a django project structure might look like when building a new django app. http://www.deploydjango.com/django_project_structure/

.

├── djangolicious

│   ├── apps

│   │   ├── blog

│   │   │   ├── __init__.py

│   │   │   ├── models.py

│   │   │   ├── tests.py

│   │   │   └── views.py

│   │   ├── __init__.py

│   │   ├── news

│   │   │   ├── __init__.py

│   │   │   ├── models.py

│   │   │   ├── tests.py

│   │   │   └── views.py

│   │   └── reader

│   │       ├── __init__.py

│   │       ├── models.py

│   │       ├── tests.py

│   │       └── views.py

│   ├── __init__.py

│   ├── libs

│   │   ├── display

│   │   │   ├── __init__.py

│   │   │   ├── models.py

│   │   │   ├── tests.py

│   │   │   └── views.py

│   │   ├── __init__.py

│   │   └── management

│   │       ├── __init__.py

│   │       ├── models.py

│   │       ├── tests.py

│   │       └── views.py

│   ├── settings

│   │   ├── common.py

│   │   ├── dev.py

│   │   ├── __init__.py

│   │   ├── prod.py

│   │   └── test.py

│   ├── urls.py

│   └── wsgi.py

├── manage.py

├── README.md

├── requirements

│   ├── common.txt

│   ├── dev.txt

│   ├── prod.txt

│   └── test.txt

├── requirements.txt


__requirements.txt__: top level file required for heroku to install dependencies
   contains a single line to install from requirements/prod.txt
   
   `-r requirements/prod.txt`
   
__djangolicious/apps/__
    module for holding django applications
    
__djangolicous/libs/__
    module or holding django libraries (helpers)
