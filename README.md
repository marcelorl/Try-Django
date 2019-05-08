# FREECODECAMP try-django

This project is from the video course from awesome freecodecamp: https://www.youtube.com/watch?v=F5mRW0jo-U4

I have just made a little change, instead of using venv I use docker.

## installation

If you want to start a new project:

```
$ docker-compose run api django-admin startproject newproject ./src
$ docker-compose run api python src/manage.py migrate
$ docker-compose run api python src/manage.py createsuperuser # u: cfe p: test1234
$ docker-compose run api python src/manage.py startapp products
$ docker-compose run api python src/manage.py makemigrations # not working yet
```
