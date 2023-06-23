Type this commands in Command Prompt
1) cd to development directory
2) mkvirtualenv 
5) pip install -r requirements.txt
6) Create and update settings.py with your email API information
Generate the google maps api key and paste it in the settings.py file
GOOGLE_API_KEY = ""
7) python manage.py makemigrations
8) python manage.py migrate
9) python manage.py runserver
10) https://localhost:8000  

Note: 

Don't forget to activate the following Google API's

Places API
Maps Javascript API
Directions API
Distance Matrix API
Geocoding API


