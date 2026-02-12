web: python manage.py migrate && python manage.py collectstatic --noinput && gunicorn MrDoc.wsgi:application --bind 0.0.0.0:$PORT --timeout 300
