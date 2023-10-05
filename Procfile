web: export DJANGO_SETTINGS_MODULE=settings.prod; echo ${DJANGO_SETTINGS_MODULE}

web: gunicorn swjsite.wsgi --log-file -

web: python manage.py runserver --settings=settings.prod