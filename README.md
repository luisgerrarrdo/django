# First Django App Tutorial

[@django project](https://docs.djangoproject.com/en/2.2/intro/)

create a new project(mysite):
```shell
  $ django-admin startproject mysite
```

create a new web application(polls):
```shell
  $ python manage.py startapp polls
```

run the server:

```shell
  $ python manage.py runserver <optional-port-number>
```

steps to create a view:

1. create a view (@/polls/views.py)
2. create urls.py file inside app folder
3. add path to urlpatterns list of app (@/polls/urls.py)
4. add path to urlpatterns list of project (@/mysite/urls.py), using include() function


three-step guide to making model changes:

1. Change your models (in models.py).
2. Run python manage.py makemigrations to create migrations for those changes
3. Run python manage.py migrate to apply those changes to the database.

