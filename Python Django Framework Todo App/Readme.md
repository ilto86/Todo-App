<h1>Steps:</h1>
<br />

<h2>Installation</h2>

```
pip install Django
django-admin startproject todoapp
```

<h2>Start</h2>

```
python manage.py migrate
python manage.py runserver
python manage.py startapp todolist
```
- add 'todolist' to INSTALLED_APPS

<h2>Add views</h2>

- implement todolist.views.py and create todolist.urls.py
- add urls to todoapp.urls.py

<h2>Add templates</h2>

- add templates folder and file
- add "templates" to DIR in settings.py
- modify view: return render...

<h2>Add models</h2>

- implement todolist.models.py

<h2>Put together</h2>

```
manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
```

- Adding models to the administration site:
 - todolist.admin.py: admin.site.register(Todo)
- login to admin

<h2>add template</h2>

- add {% csrf_token %} to template

<h2>CRUD</h2>

- implement views
