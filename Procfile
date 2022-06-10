release: python manage.py migrate --no-input
web: gunicorn fakery.wsgi
worker: celery -A fakery.celery worker -B --loglevel=info

