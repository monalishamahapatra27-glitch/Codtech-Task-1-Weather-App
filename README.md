Project: Weather Dashboard - Codtech Internship Task 1
Built by: Monalisha Mahapatra

----------------------------------------------------------------------
Description
----------------------------------------------------------------------
This is a responsive, single-page weather dashboard created as part of the Codtech IT Solutions Internship for the API Integration task. The application fetches and displays live weather data from the OpenWeatherMap API. It allows users to check the current weather and a 5-day forecast for any city worldwide or use their current location.

----------------------------------------------------------------------
Features
----------------------------------------------------------------------
- Search Weather by City: Enter a city name to get the latest weather data.
- Current Location Weather: Use the "Current Location" button to get weather information for your geographical position.
- Current Weather Details: Displays temperature, "feels like" temperature, humidity, wind speed, pressure, sunrise/sunset times, and more.
- 5-Day Forecast: Shows a forecast for the next five days, including temperature highs/lows and weather conditions.
- Responsive Design: The user interface is optimized for both desktop and mobile devices.

----------------------------------------------------------------------
How to Run
----------------------------------------------------------------------
This project is currently configured to run with mock (sample) data for demonstration purposes. To make it fully functional with live API data, follow these steps:

1.  **Get an API Key**:
    - Sign up for a free account on the OpenWeatherMap website.
    - Navigate to your account dashboard to find your unique API key.

2.  **Add the API Key**:
    - Open the `Weather.html` file in a text editor.
    - Find the line: `const API_KEY = '1234567890abcdef1234567890abcdef';`.
    - Replace the placeholder key with your actual OpenWeatherMap API key.

3.  **Enable Live API Calls**:
    - In the JavaScript section, locate the `getWeatherData`, `getWeatherByCoordinates`, and `getForecastData` functions.
    - In each function, **uncomment** the lines that start with `const response = await fetch(...)` and `const data = await response.json()`.
    - **Delete** the mock data objects (`mockData` and `mockForecast`) within those same functions.

4.  **Open the File**:
    - Save your changes and open the `Weather.html` file in any modern web browser (like Chrome, Firefox, or Edge).
