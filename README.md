# 🌦️ Weather App

A simple weather application that displays the weather based on the city name, using the [OpenWeatherMap API](https://openweathermap.org/).

## 🧩 Features

- 🔍 **Search by City**: Get up-to-date weather information by city, including:
  - Temperature
  - Humidity
  - Wind speed
- 🌤️ **Dynamic Weather Icons**: Changes the weather image based on current conditions (Rain, Clear, Clouds, etc.).
- ❌ **Error Handling**: Displays a message if the city is not found.
- 🎤 **Voice Search**: Search for weather by speaking the city name using the Web Speech API.
- 📅 **Short-Term Forecast**: Shows weather forecast for the next 3 time intervals (3, 6, 9 hours ahead).
- 🔊 **Text-to-Speech**: Read-aloud feature that speaks the current weather out loud.

## 📦 Technologies

- HTML, CSS, JavaScript
- [OpenWeatherMap API](https://openweathermap.org/api)
- Web Speech API (for voice recognition and speech synthesis)

## 🎤 Voice Search Instructions

1. Click the microphone button 🎤 next to the search bar.
2. Speak the name of the city clearly.
3. The app will automatically search and display the weather for the spoken city.

> ✅ Note: Voice recognition works best in supported browsers like Chrome.

## 🔊 Read-Aloud Instructions

1. After a successful weather result, a **"Read Aloud"** button appears.
2. Click the button and the app will read out the current temperature, city name, humidity, and wind speed.
3. Great for accessibility and hands-free use!

## 📅 Forecast Feature

- Displays forecast for the next 3 time points (3h, 6h, 9h ahead).
- Each forecast block shows:
  - Time of day
  - Expected temperature
  - Weather condition
- Forecast updates dynamically based on the searched city.

---

Feel free to expand this app further with:
- Location-based weather (using Geolocation API)
- Theme switching (dark/light)
- Multi-language support (i18n)

