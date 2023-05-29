# Deployment using render platform

Install poetry

```
curl -sSL https://install.python-poetry.org | python3 -
```

See poetry version

```
poetry --version
```

Use Poetry to initialize your project directory

```
poetry new usman_rend
```

Ifyou `ls usman_rend`, you will see

```
pyproject.toml  README.md  tests  usman_rend
```

Install django

```
poetry add django
```

Start django project

```
poetry run django-admin startproject mysite
```

run django development  server

```
poetry run mysite/manage.py runserver
```

start two django apps

```
poetry run python mysite/manage.py startapp account
poetry run python mysite/manage.py startapp blog
```

From here, update your app for render using this link guide <a href="https://render.com/docs/deploy-djangopdate-your-app-for-render">render docs</a>
- Poetry guide: https://python-poetry.org/docs/
- For more render docs: https://render.com/docs/deploy-django
