# Weather API Dashboard

This project demonstrates the use of RESTful API methods (GET, POST, PUT, DELETE) to interact with weather data and manage saved locations.

## Features

1. **GET Weather Data**: Fetches current weather data for a specified city using the OpenWeatherMap API.
2. **POST Location**: Saves a new location to a dummy API (JSONPlaceholder).
3. **PUT Location**: Updates an existing saved location.
4. **DELETE Location**: Deletes a saved location.
5. **Interactive UI**: Includes tabs for different functionalities and a modal for editing saved locations.

## Instructions

### Prerequisites
- A valid API key from [OpenWeatherMap](https://openweathermap.org/api).
- A modern web browser.
- A local server (optional for testing).

### Setup
1. Clone the repository or download the project files.
2. Replace the placeholder `API Key` in `script-Wangchuk.js` with your OpenWeatherMap API key:
   ```javascript
   const WEATHER_API_KEY = 'YOUR_API_KEY_HERE';