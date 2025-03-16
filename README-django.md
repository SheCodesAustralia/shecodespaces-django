# Installation

``` sh
pip install -r requirements.txt
python manage.py migrate
python manage.py loaddata bakeries/fixtures/bakeries.json
python manage.py runserver
```

# Admin Interface

``` sh
python manage.py createsuperuser
```

And go to localhost:8000/admin
