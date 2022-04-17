# weather-app
This is a weather application, built using Node.js, Express.js and handlebars. 
It displays the real-time forecast data, location, and temperature, of the place entered by the user, with the help of 2 APIs.

The two APIs used are:

1. Mapbox Geocoding API - 
Its forward geocoding feature was used in the application. 
The forward geocoding feature converts the location text into geographic coordinates i.e. latitude and longitude.
2. Weatherstack API -
The weatherstack API provides us with the real-time as well as the historical world weather data. Making a get request, with the geographic coordinates obtained from the Mapbox
Geocoding API passed as a query, the real-time weather forecast was obtained.

The application is deployed at - https://weather-app-vs.herokuapp.com/

How to run it on your machine:
```
1. Clone the repository
2. Run 'npm install' (on the console)
3. Run 'node src/app.js' (on the console)
4. Visit 'localhost:3000' on the browser to check the application
```
