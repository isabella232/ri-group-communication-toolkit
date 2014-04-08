web: gunicorn rapid_response_kit.app:app
web: uwsgi uwsgi.ini
web: python bin/app.py ${PORT}
web: python setup.py build
web: python setup.py install

