# 🌤️ Real-Time Weather Information App

![Java](https://img.shields.io/badge/Java-11%2B-blue.svg)
![GUI](https://img.shields.io/badge/GUI-Java%20Swing-orange.svg)
![API](https://img.shields.io/badge/API-OpenWeatherMap-brightgreen.svg)
![License](https://img.shields.io/badge/License-MIT-lightgrey.svg)

A modern, responsive Java Swing desktop application that provides real-time weather information and forecasts using the **OpenWeatherMap REST API**. Built with zero external dependencies using native Java HTTP Client.

---

## 📌 Features

- **☀️ Real-Time Weather Metrics:** Fetches live temperature, condition descriptions, humidity levels, and wind speed.
- **📅 Weather Forecast:** Displays multi-interval upcoming weather forecasts for any searched city.
- **🔄 Unit Conversion:** Toggle dynamically between **Fahrenheit (°F / mph)** and **Celsius (°C / m/s)**.
- **📜 Search History:** Automatically tracks and displays recently searched locations with timestamps.
- **🎨 Dynamic Backgrounds:** Responsive UI gradient that adjusts color schemes based on the time of day (Day, Sunset, Night).
- **⚠️ Robust Error Handling:** Input validation with clear error messages for invalid city names, empty fields, or network issues.

---

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed on your machine:
- **Java Development Kit (JDK 11)** or higher.
- A free API key from [OpenWeatherMap](https://home.openweathermap.org/users/sign_up).

---

## 🔑 API Key Configuration

1. Sign up for a free account at [OpenWeatherMap](https://openweathermap.org/).
2. Navigate to your profile and generate an **API Key**.
3. Open `WeatherApp.java` and replace `"YOUR_API_KEY_HERE"` with your actual key:

```java
// WeatherApp.java
private static final String API_KEY = "your_32_character_api_key_here";
