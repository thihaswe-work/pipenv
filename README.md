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

<ul>
<li>git clone <repo></li>
<li>cd myproject</li>
<li>pipenv install # installs everything from Pipfile.lock</li>
<li>pipenv shell</li>
<li>python manage.py runserver</li>
</ul>
