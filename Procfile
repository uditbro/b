
web: gunicorn b_project.wsgi --bind 0.0.0.0:8080

#or works good with external database
web: python manage.py migrate && gunicorn b_project.wsgi
