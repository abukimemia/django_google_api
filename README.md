Django project that uses Googles APIs to auto populate fields, display maps and routes for multiple waypoints

    1) cd to development directory
    2) mkdir django_google_api_tutorial
    3) clone repository to new directory
    4) pip install -r requirements.txt
    5) Create and update settings.ini with your email API information

GOOGLE_API_KEY = ""

RECAPTCHA_PUBLIC_KEY = ""

RECAPTCHA_PRIVATE_KEY = ""

    6) python manage.py makemigrations
    7) python manage.py migrate
    8) python manage.py runserver
    9) Enter https://localhost:8000 in your web browser

NB:
Don't forget to activate the following Google API's

reCAPTURE, Places API, Maps Javascript API, Directions API, Distance Matrix API, Geocoding API
