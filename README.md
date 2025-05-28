# Weather App 🌦️

A simple desktop weather application built with Python and `tkinter` that fetches real-time weather data using the OpenWeatherMap API. The app provides a clean graphical user interface and displays the current weather condition and temperature for any city you search.

## Features

- ✅ Real-time weather updates
- 🖼️ Background image for a personalized look
- 🌡️ Displays current temperature and main weather condition
- 🎯 Simple and responsive UI using `tkinter`

## Demo
![image](https://github.com/user-attachments/assets/e1339c1b-f19b-4925-bdbb-e02e7dfac6a7)
![image](https://github.com/user-attachments/assets/67da9af5-33e6-4955-8d19-d9a875a240ea)
![image](https://github.com/user-attachments/assets/6adf74a1-14eb-48d7-b317-d76515b6b640)

## How to Run
1. Clone or download the project files.
2. Get your own API key:
- Go to https://openweathermap.org/home/sign_in
- Sign in or create a free account
- Go to the "API keys" section in your account
- Copy your key and replace the placeholder in the script:
     ```python
     API_KEY = 'your_own_api_key_here'
     ```
3. Run the app using:
```bash
python weather_app.py
```

## Customization

🔁 **To display temperature in Celsius**, modify the API URL in the script:

Replace:
```python
units=imperial
```
With:
```python
units=metric
```

## Code Overview
- get_weather_data(city): Makes an API request and returns weather data in JSON format.
- display_weather(city): Parses and displays the weather condition and temperature.
- search_weather(): Captures city input and triggers the weather display.
- tkinter GUI handles layout and events.

## File Structure
weather_app.py

Weather_App_Bg_With_Icon.png

README.md

## License

This project is licensed under the [MIT License](LICENSE).
