web: gunicorn config.wsgi:application
worker: celery worker --app=src.taskapp --loglevel=info
