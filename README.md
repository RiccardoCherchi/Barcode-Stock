# Bardoce Stock

## installation guide

- 1 create a virtual enviroment\
```
python -m venv venv
``` 
- 2 activate the venv
```
. venv/bin/activate` (dovrebbe apparire (venv) prima dello user nel terminale)
```
- 3 install requirements
```
pip install -r requirements.txt
```
- 4 migrate for create local sqlite db
```
python manage.py migrate
```
- 5 optionally create a super user for admin panel ('/admin')
```
python manage.py createsuperuser
```
- 6 run the server
```
python manage.py runserver
```
(optionally: 0.0.0.0:port -> for outsude localhost)
