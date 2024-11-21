Weather App
A simple weather application built with Python that fetches real-time weather data from the OpenWeatherMap API. The app takes a city name as input and displays the current weather information, including temperature, humidity, pressure, wind speed, and more.

Features
Fetches real-time weather data from the OpenWeatherMap API.
Displays the current temperature, pressure, humidity, wind speed, and weather description.
Provides error handling for invalid city names.
Simple command-line interface for user interaction.
Requirements
Python 3.x
requests library to handle HTTP requests.
An API key from OpenWeatherMap.
Installation
Step 1: Clone the Repository (Optional)
If you want to clone the repository to your local machine, run:


git clone https://github.com/julisunkan/weather-app.git cd weather-app
Step 2: Install Dependencies
The app requires the requests library, which can be installed using pip:


pip install requests
Step 3: Get OpenWeatherMap API Key
Go to OpenWeatherMap and sign up for a free account.
After signing up, generate an API key.
Replace the placeholder your_api_key_here in the code with your actual API key.

api_key = "your_api_key_here" # Replace this with your actual API key
Step 4: Run the App
Once the dependencies are installed and the API key is added, run the app using Python:


python weather_app.py
The app will prompt you to enter a city name. After entering the city, it will display the current weather information for that location.

Usage
When prompted, enter the name of the city for which you want to get weather information.
The app will display the following details:
Temperature (°C)
Pressure (hPa)
Humidity (%)
Weather Description (e.g., clear sky, cloudy, etc.)
Wind Speed (m/s)
Cloudiness (%)
Example:

Enter the city name: London Weather Info for London: Temperature: 15.5°C Pressure: 1015 hPa Humidity: 76 % Weather: Clear sky Wind Speed: 3.1 m/s Cloudiness: 0%
Error Handling
If an invalid city name is provided, the app will display an error message like:

Invalid city name. Please check the spelling or try another city.
License
This project is open-source and available under the MIT License.

Acknowledgments
The weather data is provided by the OpenWeatherMap API.
This app was built with the help of Python's requests library.
