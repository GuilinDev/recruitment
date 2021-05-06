## recruitment
### Django 3.1
### Django Admin

#### run locally
```shell script
python manage.py runserver 0.0.0.0:8000
```
> access at http://127.0.0.1:8000/admin

#### Migrate database to sqllite and validate
```shell script
python manage.py makemigrations
```

```shell script
python manage.py migrate
```