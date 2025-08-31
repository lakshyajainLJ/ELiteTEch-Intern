# 🌦️ Weather Forecast Visualization (Python + OpenWeatherMap)

A Python project that fetches **5-day weather forecast data** from the [OpenWeatherMap API](https://openweathermap.org/api) and visualizes **temperature** and **humidity** trends using **Matplotlib**.  

This is a simple yet practical project to practice working with APIs, JSON data handling, and Python data visualization.  

---

## ✨ Features

- 📡 Fetches 3-hour interval forecasts for the next 5 days  
- 🌡️ Plots **temperature (°C)** trends  
- 💧 Plots **humidity (%)** trends  
- 🏙️ Easily change the city by updating one variable  
- 📊 Clean and easy-to-read visualizations  

---

## 📦 Requirements

- Python 3.8+  
- Install dependencies:
```bash
pip install requests matplotlib
(Optional): Install seaborn for enhanced plot styling:


pip install seaborn
🚀 Usage
Get an API key
Sign up at OpenWeatherMap to get a free API key.

Update the script
Open the Python file and set your API key and city:


API_KEY = "YOUR_API_KEY"
CITY = "Delhi"
Run the script


python weather_forecast.py
View the plots
Two plots will be displayed:

Temperature over time (°C)

Humidity over time (%)

📊 Example Output

Red = Temperature, Blue = Humidity

🔮 Future Improvements
Add rainfall and wind speed charts

Save plots automatically as PNG/PDF

Interactive charts with Plotly or Bokeh

Dockerize for easier deployment