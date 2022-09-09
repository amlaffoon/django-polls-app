1. create venv: (only do once)

```powershell
python -m venv venv
```
2. activate venv (run every time)

```powershell
.\venv\Scripts\activate
```
3. install django

```
python -m pip install Django
```

4. pip freeze (dependency requirements)

```
python -m pip freeze > requirements.txt
```

5. create project
```
django-admin startproject [mysite]
```
6. start server
```
python manage.py runserver
```