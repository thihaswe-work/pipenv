# PIPENV

## ✅ 1. Create project

```bash
django-admin startproject myproject
cd myproject

```

## ✅ 2. Install Django with Pipenv

```bash
pipenv install django

```

## ✅ 3. Run shell

```bash
pipenv shell


```

## 🟥 4. Add .gitignore

```bash
__pycache__/
*.pyc
db.sqlite3
# Pipenv stores venv somewhere else, so no need to ignore venv/

```

## When someone wants to clone my repo

git clone <repo>
cd myproject
pipenv install # installs everything from Pipfile.lock
pipenv shell
python manage.py runserver
