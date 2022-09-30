web: gunicorn restapi.wsgi:application -b 0.0.0.0:$PORT --log-file - --log-level debug
manage.py migrate
