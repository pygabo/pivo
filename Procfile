web: gunicorn pivo.wsgi --limit-request-line 8188 --log-file -
worker: celery worker --app=pivo --loglevel=info
