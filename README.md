# reachout-backend

## Setup 

```bash
virtualenv -p python3 venv
source venv/bin/active
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser
```

## Running

```bash
source venv/bin/activate
python manage.py test
python manage.py runserver
```