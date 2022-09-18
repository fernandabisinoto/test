web: gunicorn web_project.wsgi
heroku ps:scale web=1
release: python manage.py migrate
