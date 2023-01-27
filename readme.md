### To create django project

"""
shell
## linux command

django-admin statproject velocity 

## windows command

django-admin.exe  startproject velocity
"""

## project structure

""" markdown

Mini_django-V1 (Project-directory)

    -readme.md
    -requirements.txt
    -venv
    -velocity (Project)
        -manage.py
        -velocity (project settings)
            -__init__.py
            -asgi.py
            -wsgi.py
            -settings.py
            -urls.py 
"""

### django files

- 'manage.py' :: this scripts helps us to with management of site
   it helps us to start web server.
- 'settings.py' :: contains confgruation for the website
- 'urls.py':: this is file for url management
- 'wsgi.py' :: deployment purpose
- 'asgi.py' :: deployment purpose

### default database with django
- sqlite

### how to create tables associated with sub-applications?
- django has pre-built sub-applications availabel in itself
- we can create database tables using those apps by using following command

'''shell

cd <project-directory>  #  cd velocity
python manage.py migrate
'''

- to run the application

'''shell
python manage.py runserver
'''

## Synopsis to start with django
- step 1 :- Create directory mkdir <project-root>
- step 2 :- cd to directory in step 1
- step 3 :- django-admin.exe startproject velocity
- step 4 :- cd velocity
- step 5 :- create DB tables python manage.py migrate
- step 6 :- run project python manage.py runserver
- 