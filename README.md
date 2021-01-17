## Geek Beacon Fest Ghost Site

TODO: write a better README.


Development: 


1. ln -s development.yaml docker-compose.yml
2. cp env.tempate .env 
3. docker-compose up -d 

check emails at http://localhost:8025, see ghost website at http://localhost:8888

Admin interface can be found here:

http://localhost:8888/ghost.  You will get a 404 for the home page until you create a page with the slug 'home'.