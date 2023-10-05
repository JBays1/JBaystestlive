web: export DJANGO_SETTINGS_MODULE = settings.prod; gunicorn swjsite.wsgi --log-file -

web: python manage.py runserver --settings=settings.prod