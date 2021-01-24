# Ecommerce-Backend

## TODO add pre-req install instructions
## Setup:
```
mkvirtualenv venv --python=`which python3`
workon venv
pip install config/requirements.txt
cd src/
python manage.py makemigrations
python manage.py migrate
python manage.py runserver 0.0.0.0:8000
```

### Docker setup:
````
docker-compose up -d --build
docker-compose exec backend sh
# cd src/
# python manage.py makemigrations
# python manage.py migrate
````