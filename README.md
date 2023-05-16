# leafmap-implementation-with-streamlit-using-weather-api
This is a sample project on static sample data from weather api (files named "tr.geojson" & "EgyptCitiesExampleData.geojson". Built with python using leafmap library for webmaps.

## App functionalities:

#### hosting
- The app is hosted on streamlit, which -at the same time- provides a python library for creating the UI of the app, including buttons and menus.
#### libraries used 
- The leafmap library provied the api to build the webamp, addin base-maps, and provides the map controls such as measurements, zooming, creating features and search boxes.
#### user interactions
- The app allow for user uploaded geojsons, up to 200MB, that holds a location and geometry data to be displayed.This is the way to form a heat map.
-  User can search by city name. The geocoding is possible with the help of the weather api itself, as it return the city's location along with its weather information.

## Want to try the app?
- Check it on streamlit: https://ahmedh7-leafmap-implementation-with-streamlit-temprature-zz1a2x.streamlit.app/
