# Historical_data_weather_app_2025

A Streamlit-based web application for analyzing weather data using OpenWeatherMap API and historical data from Meteostat. This application allows users to:
-Retrieve current temperature for any city using OpenWeatherMap API.
-Load and analyze historical weather data, either from a CSV file or Meteostat API.
-Visualize historical temperature trends with seasonal profiles (average and standard deviation ranges).
-Identify temperature anomalies and check if the current temperature is normal for the selected season.
-Customize the analysis period (1–50 years) for historical weather data.
-Filter and display data for specific cities from uploaded datasets.

Key Features:
-Dynamic Graphs: Visualize historical weather data with clear anomaly highlights.
-Seasonal Analysis: Understand seasonal temperature variations with visually distinct seasonal profiles.
-User-Friendly Interface: Select cities from a list or manually enter a city name.
-Interactive Controls: Upload CSV data or use real-time API data with an adjustable historical period slider.

Technologies Used:
-Python
-Streamlit for the user interface
-Pandas for data processing
-Matplotlib for visualization
-Meteostat for historical weather data
-OpenWeatherMap API for real-time weather data
