# Enhanced Weather Dashboard with OpenWeatherMap API

## Overview
This is an enhanced, responsive weather dashboard web app which uses data from the OpenWeatherMap API. New features include historical weather data charts, air quality index display, UV index warnings, hourly forecast for next 24 hours, dark mode toggle, ability to store favorite locations using localStorage, real-time weather alerts, and the ability to export weather data to CSV.

This updated dashboard provides a comprehensive weather outlook for any city, including current air quality and temperature, UV warnings, a 24-hour forecast, along with weather trends and warnings. It's particularly useful for planning outdoor activities and trips.

## Setup
Replace `'your_openweathermap_api_key'` in the javascript section of `index.html` with your own OpenWeatherMap API Key.

## Usage

1. Enter a city name in the input field and click on 'Search'. The current weather, air quality index, UV index warnings, and a 5-day forecast for that city will be displayed.
2. Click on 'Show Historical Data' button to view historical weather data charts.
3. Click on 'Dark Mode' toggle to switch to dark theme.
4. Click on 'Add to Favorites' button to save the current city as favorite. Your favorite cities will persist across sessions.
5. The dashboard will show real-time weather alerts if there are any for your city.
6. Click on 'Export to CSV' button to download weather data for the currently viewed city.

## Improvements from Previous Version

1. Added charts to depict historical weather data.
2. Introduced air quality index display with proper color coding.
3. Implemented UV index warnings.
4. Now provides an hourly forecast for the next 24 hours.
5. Implemented a dark mode toggle for better user experience in different lighting conditions.
6. Enabled storing and retrieval of favorite locations using localStorage.
7. Implemented real-time weather alerts and notifications.
8. Added a feature to export weather data to a CSV file.