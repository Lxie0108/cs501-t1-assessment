web: gunicorn --chdir project server:app
heroku ps:scale web=1
release: ./launch.sh db upgrade