
## Django Application with Google Places API and Dynamic Programming for Optimal Path to solve Travelling Salesman Problem


I would like to introduce my Django application that utilizes the Google Places API and implements dynamic programming with bitmasking to find the optimal path for visiting seven places in the United States. The application then uses the Google Maps API to provide directions and visualize the final path.

Type this commands in Command Prompt

Sample Run Example->
<img src="https://github.com/parthjain99/Travelling-Salesman-Problem-Frontend/blob/main/Place.png"> </img>
<img src="https://github.com/parthjain99/Travelling-Salesman-Problem-Frontend/blob/main/Output.png"> </img>



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

Project Overview:

This Django application aims to solve the Traveling Salesman Problem (TSP) for a given set of seven locations in the United States. The goal is to find the shortest path that visits all seven locations and returns to the starting point.

Features:

Google Places API Integration: The application integrates with the Google Places API to fetch the distance matrix between the seven locations. This matrix provides the distance between each pair of locations, which is essential for solving the TSP.

Dynamic Programming and Bitmasking: To find the optimal path, the application uses dynamic programming with bitmasking. By considering all possible subsets of the locations and storing the optimal path length for each subset, the algorithm efficiently computes the shortest path.

Direction and Visualization: Once the optimal path is determined, the application utilizes the Google Maps API to display the directions for the path and visualize the final route on a map. Users can easily follow the directions and understand the sequence of locations to visit.
