# Travel Advisor

https://www.youtube.com/watch?v=UKdQjQX1Pko

## Introduction
Build and Deploy an advanced Travel Companion Application using Google Maps. With Geolocation, Google Maps API, Searching for places, Fetching restaurants, hotels and attractions based on location from specialized Rapid APIs, data filtering and much more, this Travel Advisor App is the best Maps Application that you can currently find on YouTube and on the entire internet.

In this video, you'll learn:

- Advanced React Best Practices such as folder & file structure, hooks and refs
- Creating a User Interface using Material UI
- Working with Google Maps API
- And most importantly fetching data from unlimited sources using RapidAPI
- Essentially, you'll become the master of working with APIs


## API used
RapidAPI: https://rapidapi.com/
Get Places Data to display in Google Map: Travel Advisor API: https://rapidapi.com/apidojo/api/travel-advisor?utm_source=youtube.com/JavaScriptMastery&utm_medium=DevRel&utm_campaign=DevRel
Get Weather Forcast Data to display in Google Map: Open Weather Map API: https://rapidapi.com/community/api/open-weather-map?utm_source=youtube.com/JavaScriptMastery&utm_medium=DevRel&utm_campaign=DevRel

Google Map: get a "Maps JavaScript API" key from google deveveloper
- create project
- add 2 google APIs:
  . "Maps JavaScript API"
  . "Places API"
- Credentials > + Create Credendial > API Key
https://console.cloud.google.com/google/maps-apis/credentials?project=optimal-plate-314414

## env file application keys
- REACT_APP_GOOGLE_MAPS_API_KEY : used in GoogleMapReact > bootstrapURLKeys and has to be same value as from index.html > <script src="https://maps.googleapis.com/maps/api/js?v=3.exp&libraries=geometry,drawing,places&key=XXXXXXXXXXXXXX"></script>, this script tag must be added in index.html
- REACT_APP_RAPID_API_TRAVEL_API_KEY : value from rapidapi.com > x-rapidapi-key
- REACT_APP_RAPID_API_WEATHER_API_KEY : value from rapidapi.com > x-rapidapi-key  (same as previous one since using same rapidapi account)

## Shange map styles
Quick way to manage google map styles
- add "mapStyles" object in GoogleMapReact > options={{ disableDefaultUI: true, zoomControl: true, styles: mapStyles }}
- content of mapStyles.js is retrieved from https://snazzymaps.com/ which is a provider for google map : see https://youtu.be/UKdQjQX1Pko at 2:05
  . I took this one: https://snazzymaps.com/style/1243/xxxxxxxxxxx
