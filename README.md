# SmartWeather | Xavier's Weather Forecast

A responsive weather forecast web application that allows users to search weather by city or use their current location and built with HTML, Tailwind CSS, and JavaScript.

---

## Features

- Search current weather by city name
- Detect and display weather for current location using geolocation
- Display 5-day weather forecast with temperature, humidity, wind speed, and condition icons
- Recent searched cities dropdown stored locally for quick access (up to 5 cities)
- Responsive design compatible with desktop, tablet, and mobile devices
- User-friendly error messages for invalid input or API failures



## Installation & Setup

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/smartweather.git
cd smartweather

Open the project

You can open the project folder in VS Code or any preferred code editor.

API Key

The app uses WeatherAPI. You need an API key to fetch data:

Sign up at WeatherAPI.com for a free API key.

Replace the placeholder API key in the script section of index.html:

const apiKey = '6ead48b9b18f42e49ae152444251705';

Run the app

Open the index.html file in your browser (double-click or use Live Server extension in VS Code).

Usage
Enter a city name and click Search Weather or press Enter.

Or click Detect Location to use your current location for weather data.

Select previously searched cities from the dropdown to quickly fetch their weather.

Technologies Used
HTML5

Tailwind CSS (via CDN)

JavaScript (Fetch API, DOM manipulation)

WeatherAPI (weather data provider)

LocalStorage (for saving recent searches)

Folder Structure
/smartweather
  ├── index.html        # Main HTML file
  ├── README.md         # This file
  └── assets/           # Images, icons (optional)
Known Issues / Future Improvements
Add unit toggle (Celsius/Fahrenheit)

Improve accessibility features (ARIA roles, keyboard nav)

Add more detailed hourly forecast

Optimize performance with caching

License
This project is licensed under the MIT License.

Contact
Created by Xavier — feel free to reach out:

Email: xavier.siby777@gmail.com
