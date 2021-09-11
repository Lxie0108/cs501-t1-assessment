web: gunicorn --chdir project server:app
heroku ps:scale web=1
release: python manage.py db upgrade