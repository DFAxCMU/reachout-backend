# reachout-backend

## Setup 

```bash
virtualenv -p python3 venv
source venv/bin/activate
pip install -r requirements.txt
cd reachout
python manage.py migrate
python manage.py createsuperuser
```

## Running

```bash
source venv/bin/activate
cd reachout 
python manage.py test
python manage.py runserver
```