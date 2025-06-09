## Python Django

```
py --version
py -m venv .venv

.venv\Scripts\Activate.ps1     або .venv\Scripts\activate.bat

python.exe -m pip install --upgrade pip
py -m pip install Django

py -m django --version
```

## Working GitHub
```
git status
git init
git status
git add .
git status
git commit -m"Init Project"

git branch -M main
git remote add origin https://github.com/novakvova/Django_SPD311.git
git push -u origin main

```

## Create Project Django
```
mkdir cats
django-admin startproject mysite cats

cd cats
py manage.py runserver 4893
```

## Робота з БД. Підключення і налаштування
```
"Host=ep-lively-darkness-a27mmu8y-pooler.eu-central-1.aws.neon.tech;Database=neondb;Username=neondb_owner;Password=npg_bqhGu6KCc8nM"

pip install psycopg2-binary
pip install Pillow

py manage.py startapp users

py manage.py makemigrations users

py manage.py sqlmigrate users 0001

py manage.py migrate

```

## Clone poject GitHub
```

git clone https://github.com/novakvova/Django_SPD311.git
cd Django_SPD311

py -m venv .venv
.venv\Scripts\activate.bat

python.exe -m pip install --upgrade pip
py -m pip install Django
pip install psycopg2-binary
pip install Pillow

cd cats

py manage.py runserver 4893

```