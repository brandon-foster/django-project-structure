django-project-structure
========================

What a django project structure might look like when building a new django app. http://www.deploydjango.com/django_project_structure/

.

├── djangolicious

│   ├── apps

│   │   ├── blog

│   │   │   ├── \_\_init\_\_.py

│   │   │   ├── models.py

│   │   │   ├── tests.py

│   │   │   └── views.py

│   │   ├── \_\_init\_\_.py

│   │   ├── news

│   │   │   ├── \_\_init\_\_.py

│   │   │   ├── models.py

│   │   │   ├── tests.py

│   │   │   └── views.py

│   │   └── reader

│   │       ├── \_\_init\_\_.py

│   │       ├── models.py

│   │       ├── tests.py

│   │       └── views.py

│   ├── \_\_init\_\_.py

│   ├── libs

│   │   ├── display

│   │   │   ├── \_\_init\_\_.py

│   │   │   ├── models.py

│   │   │   ├── tests.py

│   │   │   └── views.py

│   │   ├── \_\_init\_\_.py

│   │   └── management

│   │       ├── \_\_init\_\_.py

│   │       ├── models.py

│   │       ├── tests.py

│   │       └── views.py

│   ├── settings

│   │   ├── common.py

│   │   ├── dev.py

│   │   ├── \_\_init\_\_.py

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


\_\_requirements.txt\_\_: top level file required for heroku to install dependencies
   contains a single line to install from requirements/prod.txt
   
   `-r requirements/prod.txt`
   
\_\_djangolicious/apps/\_\_
    module for holding django applications
    
\_\_djangolicous/libs/\_\_
    module or holding django libraries (helpers)
