
web: gunicorn --bind 0.0.0.0:$PORT restapi.wsgi:app
heroku ps:scale web=1
python manage.py migrate