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
│   ├── settings.py
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
└── TREE.txt

9 directories, 34 files
