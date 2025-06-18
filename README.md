# 🌤️ Weather Data Fetcher (OpenWeatherMap API)
A lightweight and structured Python script that retrieves current weather conditions for any city using the OpenWeatherMap API. It includes geocoding support to convert city/state/country into coordinates and returns detailed weather information.

## ✅ Features
📍 Geocoding Support
Converts city, state, and country into latitude and longitude using OpenWeatherMap's Geocoding API.

## 🌡️ Current Weather Data
Fetches:
- Main weather type (e.g., Rain, Clear)
- Detailed description (e.g., light rain)
- Temperature in Celsius
- Weather icon code

## 🧩 Structured Output
- Uses Python @dataclass for clean and structured weather data modeling.

## 🧰 Technologies Used
| Tool          | Purpose                            |
| ------------- | ---------------------------------- |
| Python        | Core language                      |
| requests      | For making HTTP API requests       |
| dataclasses   | Structured and typed data modeling |
| python-dotenv | Secure API key management          |

## 🔍 Example Output
{
  "city": "London",
  "temperature_celsius": 17.3,
  "main": "Clouds",
  "description": "overcast clouds",
  "icon": "04d"
}


## 🛠 Future Enhancements
- Add weather forecast (5-day)
- CLI or GUI interface
- Weather alerts (if supported by API)
- Unit tests
