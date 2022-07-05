release: python manage.py migrate
web: gunicorn my chat-application.wsgi:application --log-file=-s