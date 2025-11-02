# Weather Forecast using OpenWeatherMap API

This Python application retrieves and displays current weather information using the OpenWeatherMap API. The user can choose to search by city and state or by ZIP code. The program first performs a geolocation lookup to obtain latitude and longitude, then retrieves the corresponding weather data.

Users can view temperature in Celsius, Fahrenheit, or Kelvin, and the output includes the city, state, current temperature, “feels like” temperature, high and low temperatures, pressure, humidity, and weather description.

The program uses the Requests library to connect to the web service and includes robust error handling with specific exception messages for failed connections or invalid input. It validates user entries to prevent crashes and allows repeated lookups for multiple locations.
The code follows PEP 8 conventions, includes meaningful comments, and is organized with multiple functions. The program was written on Python 3.
