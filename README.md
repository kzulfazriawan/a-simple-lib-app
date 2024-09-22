# QTDR (Quick-Time Django REST)

_QTDR_ is pre-fabricated django-rest-framework for quick development in projects. _QTDR_ is providing pre-sets URLS, Views
Abstract Audit Model with UUID, and template generate for setup the views and serializer model, by separating the module
we believe _QTDR_ will create best efficiency in project from start to finish.

# Installation
For docker
```shell
docker compose up -d
docker compose up run --rm python manage.py makemigrations
docker compose up run --rm python manage.py migrate
docker compose up run --rm python manage.py loaddata fixtures/superuser.yaml
```

For non-docker
```shell
python manage.py makemigrations
python manage.py migrate
python manage.py loaddata fixtures/superuser.yaml
```