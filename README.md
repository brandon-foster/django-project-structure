django-project-structure
========================

What a django project structure might look like when building a new django app. http://www.deploydjango.com/django_project_structure/

__requirements.txt__: top level file required for heroku to install dependencies
   contains a single line to install from requirements/prod.txt
   `-r requirements/prod.txt`
   
__djangolicious/apps/__
    module for holding django applications
    
__djangolicous/libs/__
    module or holding django libraries (helpers)
