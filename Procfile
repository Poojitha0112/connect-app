release: python manage.py migrate
web: gunicorn tdl.wsgi --log-file -
worker: python manage.py runworker channels --settings=core.settings -v2