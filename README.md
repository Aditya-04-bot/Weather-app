# 🌦️ Weather App

A responsive **Weather Web Application** that allows users to view
real-time weather information based on their **current location** or by
**searching any city worldwide**. The app uses the **OpenWeatherMap
API** to fetch live weather data and displays temperature, humidity,
wind speed, and cloud conditions in a clean UI.

------------------------------------------------------------------------

## 🚀 Features

✅ Get weather using **current location (Geolocation API)**\
✅ Search weather by **city name**\
✅ Displays:

-   City name & country flag
-   Weather description
-   Temperature (°C)
-   Wind speed
-   Humidity
-   Cloudiness

✅ Tab-based UI: - Your Weather - Search Weather

✅ Session storage support for faster repeat access\
✅ Responsive and modern UI design\
✅ Loading indicator while fetching data

------------------------------------------------------------------------

## 🛠️ Tech Stack

-   HTML5
-   CSS3
-   JavaScript (Vanilla JS)
-   OpenWeatherMap API
-   Geolocation API
-   Session Storage API

------------------------------------------------------------------------

## 📁 Project Structure

weather-app/ │ ├── index.html ├── styles.css ├── script.js │ ├── assets/
│ ├── cloud.png │ ├── humidity.png │ ├── wind.png │ ├── location.png │
├── search.png │ ├── loading.gif │ └── not-found.png │ └── README.md

------------------------------------------------------------------------

## 🔑 API Setup

This project uses the OpenWeatherMap API.

### Steps to configure:

1.  Go to https://openweathermap.org/api
2.  Create a free account
3.  Generate your API key
4.  Replace inside script.js:

const API_KEY = "YOUR_API_KEY_HERE";

------------------------------------------------------------------------

## ▶️ How to Run Locally

Clone the repository:

git clone https://github.com/your-username/weather-app.git

Navigate to folder:

cd weather-app

Open index.html in your browser or use Live Server.

------------------------------------------------------------------------

## 🌍 How It Works

### Current Location Weather

1.  Click **Your Weather**
2.  Allow location access
3.  App stores coordinates in session storage
4.  Weather loads automatically next time

### Search Weather by City

1.  Click **Search Weather**
2.  Enter city name
3.  View live weather instantly

------------------------------------------------------------------------

## 📦 Future Improvements

-   Add 5-day forecast
-   Add temperature unit toggle (°C / °F)
-   Dark/light mode
-   Error handling UI for invalid city
-   Add recent searches history
-   Deploy live version (GitHub Pages)

------------------------------------------------------------------------

## 👨‍💻 Author

Your Name\
https://github.com/your-username
