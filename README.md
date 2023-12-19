# Charlottesville Travel Itinerary Maker 
This project allows regular users to go in and automatically generate an itinerary for a set of days that they are visiting fitting certain criteria that they choose. Users are also able to reccomend new locations, which will can be reviewed and either approved or rejected from being in the pool of locations from with the itinerary is generated.

## Contributors:
- Jaeson Martin 
- Silda Neza 
- Kaicheng Chu

## TO RUN:
- Local development will require first creating a Super User account using 'python manage.py createsuperuser'. After this, you can run, 'pyton manage.py migrate', then 'python manage.py makemigrations' and lastly 'python manage.py runserver'. Now navigate to 'http://127.0.0.1:8000/admin'. From here set up the social application with the necessary credentials to allow for the Google Maps API to work correctly. The application can now be used locally using a sqlite database as the means of data persistence.


- To view the currently deployed version of the application deployed on Heroku, visit 'https://a12plannerapp-7070b47869a6.herokuapp.com/'


## Note on Security
It is known that some of the secret keys (such as the Google OAuth Key) are exposed in this repository which could be a major problem for the remote, live application. However, since the purpose of this project is to serve as more of a demo, it was decided to leave these secrets in the repository so that it is possible to run the application locally with ease for anyone that comes across it. 
