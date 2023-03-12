release: python manage.py migrate
web: gunicorn core.wsgi --log-file -
worker: python manage.py runworker channels --settings=core.settings -v2