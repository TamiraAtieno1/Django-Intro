 Create a vitrual environment-> python -m venv venv (to set up a module storage)
 Activate the venv-> source venv/Scripts/activate (CRUCIAL)
 Install Django-> pip install django
 Create a project-> django-admin startproject {appname}
 Cd into project created
 Create an app-> python manage.py startapp {appname}
 Connect the app to the project-> add the app to the INSTALLED_APPS list in settings.py
 Create a view-> create a function in views.py
 Create a URL-> create a path in urls.py
 Create a template-> create a template in templates folder