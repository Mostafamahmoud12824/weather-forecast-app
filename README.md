# 🌦️ Weather Forecast App  

A simple and responsive weather website that allows users to search for real-time weather forecasts. Built with **HTML, CSS, and JavaScript**. 🌍☀️🌧️  

---

## 🎯 Happy Coding! 🚀  

We hope you enjoy using the Weather Forecast App. Feel free to contribute or enhance the project! 😊  

---

## 📧 Contact  

👤 **Mostafa Mahmoud Salah**  
📧 [Email](mm4581@fayoum.edu.eg)  
🔗 [GitHub](https://github.com/Mostafamahmoud12824)  
🔗 [LinkedIn](https://www.linkedin.com/in/mostafa-mahmoud-salah-1234567d89/)  

---

## 💡 Future Improvements  

>✅ Add a **dark mode** feature.  
>✅ Improve the **UI/UX design**.  
>✅ Integrate **geolocation API** for auto-detecting the user's location.  
>✅ Include **hourly weather updates**.  

---

## 📜 How to Use  

>### 1️⃣ Clone the repository:  git clone https://github.com/Mostafamahmoud12824/weather-forecast-app.git
>### 2️⃣ Open index.html in a browser.
>### 3️⃣ Type a city name in the search box to fetch its weather forecast.

---

## 📌 Summary
The Weather Forecast App is a real-time, interactive weather application that allows users to check the weather for any city using WeatherAPI. It dynamically updates the UI as users type and provides both current conditions and a 3-day forecast.

----

## 📂 Project Structure
graphql
Copy
Edit
📦 Weather Forecast App  
│── 📄 index.html          # Main HTML file  
│── 📄 index.js            # JavaScript logic for fetching & displaying weather  
│── 📂 css/                # Stylesheet files  
│── 📂 images/             # Icons and assets  
│── 📂 js/                 # JavaScript dependencies  
│── 📄 README.md           # Documentation


## ⚙️ Functionality
###  1️⃣ Fetching Weather Data
` When a user enters a location in the search bar, the app makes an API call to retrieve weather data using:
js
Copy
Edit
fetch(`https://api.weatherapi.com/v1/forecast.json?key=YOUR_API_KEY&q=${location}&days=3`);
Retrieves weather data for the next 3 days.
Updates the UI dynamically.`

### 2️⃣ Displaying Current Weather
> The function displayCurrent(location, currentWeather):
> Extracts the current temperature.
> Displays an icon representing the weather condition.
> Shows wind speed, direction, and rain probability.
> Updates the UI dynamically.

### 3️⃣ Displaying Future Weather
> The function displayAnother(forecastData):
> Loops through forecast data and creates UI elements.
> Displays the high and low temperatures for upcoming days.
> Shows an icon representing the forecasted weather condition.

### 4️⃣ Real-Time Search
The app listens for user input and updates the weather forecast dynamically:
js
Copy
Edit
document.getElementById("search").addEventListener("keyup", (event) => {
    search(event.target.value);
});

### 5️⃣ Default City on Load
> When the page loads, the app automatically fetches and displays the weather for Cairo by calling:
> js
> Copy
> Edit
> search("cairo");
> 🔗 Live Demo
> 🚀 View the live project

## 🎯 Happy Coding! 🚀
This **README** follows your specified order:  
1. 🎯 **Happy Coding! 🚀**  
2. 📧 **Contact**  
3. 💡 **Future Improvements**  
4. 📜 **How to Use**  
5. 📌 **Summary**  
6. 📂 **Project Structure**  
7. ⚙ **Functionality**  

****
 ####  Let me know if you need **any further modifications**! 🚀😊 








