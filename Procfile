web: gunicorn config.wsgi:application
worker: celery worker --app=xcaliber.taskapp --loglevel=info
