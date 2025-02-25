# weather-forecast-app
🌦️ A simple and responsive weather website that allows users to search for real-time weather forecasts. Built with HTML, CSS, and JavaScript. 🌍☀️🌧️  Let me know if you want a different name or more details! 🚀
Functionality of the Weather App
Your Weather Forecast App is a simple, interactive weather application that fetches and displays real-time weather data for a user-specified location. Below is a breakdown of how it works:

🌍 Features
✔️ Real-time Weather Data – Fetches current weather and a 3-day forecast using the WeatherAPI.
✔️ Dynamic UI Update – Displays weather conditions dynamically as the user types.
✔️ Search Functionality – Users can search for a city, and the app updates weather details in real time.
✔️ Auto-Load Default City (Cairo) – When the page loads, the weather for Cairo is automatically displayed.

⚙️ How It Works
1️⃣ Fetching Weather Data (search(location))
When a user enters a location in the search bar, the app makes an API call to WeatherAPI using:
js
Copy
Edit
fetch(`https://api.weatherapi.com/v1/forecast.json?key=YOUR_API_KEY&q=${location}&days=3`);
It retrieves weather data for the next 3 days and updates the UI.
2️⃣ Displaying Current Weather (displayCurrent(location, currentWeather))
This function:
Extracts the current temperature.
Displays an icon representing weather conditions.
Shows wind speed, direction, and rain probability.
Updates the UI dynamically.
3️⃣ Displaying Future Weather (displayAnother(forecastData))
This function:
Loops through forecast data and creates HTML elements.
Displays the high and low temperatures for the upcoming days.
Shows an icon representing the forecasted weather condition.
4️⃣ Real-Time Search (document.getElementById("search").addEventListener("keyup", ...))
Whenever the user types in the search bar, the app automatically updates the weather details.
5️⃣ Default City on Load
When the page loads, the app automatically fetches and displays the weather for Cairo by calling:
js
Copy
Edit
search("cairo");
📌 Summary
Your app is a real-time, interactive weather application that allows users to check the weather for any city using the WeatherAPI. It dynamically updates the UI as users type and provides both current conditions and a 3-day forecast.

Would you like any improvements, such as styling enhancements, additional features, or API optimizations? 🚀
