```
python3 -m venv venv
venv/bin/python -m pip install --upgrade pip
venv/bin/python -m pip install -r requirements.txt

python manage.py migrate
python manage.py createsuperuser

python manage.py runserver
```
