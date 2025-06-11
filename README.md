Weather Data Fetcher (OpenWeatherMap API)
A lightweight Python script that retrieves the current weather conditions (temperature, description, weather type, and icon) for any given city using the OpenWeatherMap API.

Features
- Convert city + state + country into coordinates using OpenWeatherMap Geocoding API
- Fetch current weather data using OpenWeatherMap Current Weather API
- Returns main weather type, detailed description, temperature (°C), and icon code
- Clean and well-structured using @dataclass for the weather object

Technologies Used
- Python 
- requests – for HTTP requests
- dataclasses – for structured weather data
- python-dotenv – for managing your API key securely

