web: python manage.py syncdb --migrate --settings=idea.settings.cf && waitress-serve --port=$VCAP_APP_PORT idea.settings.wsgi_cf:application
