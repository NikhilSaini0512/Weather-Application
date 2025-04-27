# SkyCast - Weather Forecast

## Overview

SkyCast is a weather forecasting web application that provides real-time weather updates and a 5-day forecast for any city. The application utilizes the OpenWeatherMap API to fetch weather data and displays it in a user-friendly interface.

## Features

- **Current Weather**: Displays the current temperature, weather description, humidity, wind speed, and pressure.
- **5-Day Forecast**: Provides a forecast for the next five days with temperature and weather icons.
- **Location Services**: Users can get weather updates based on their current location.
- **Search Functionality**: Users can search for weather updates by city name.
- **Responsive Design**: The application is designed to work on various screen sizes.

## Technologies Used

- HTML
- CSS
- JavaScript
- OpenWeatherMap API
- Font Awesome for icons

## Getting Started

### Prerequisites

- A web browser
- An internet connection

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/NikhilSaini0512/Weather-Application.git
   ```

2. Navigate to the project directory:
   ```bash
   cd skycast
   ```

3. Open `index.html` in your web browser.

### API Key

To use the OpenWeatherMap API, you need to sign up for an API key. Replace the placeholder API key in the JavaScript code with your actual API key:

```javascript
const API_KEY = 'your_api_key_here';
```

## Usage

- Open the application in your web browser.
- Click on "My Location" to get the weather for your current location.
- Use the search bar to enter a city name and get the weather forecast for that city.

## Troubleshooting

- If you encounter a **403 Client Error: Forbidden** when loading Font Awesome, ensure that the link to the Font Awesome CDN is correct or consider downloading the icons locally.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [OpenWeatherMap](https://openweathermap.org/) for providing the weather data.
- [Font Awesome](https://fontawesome.com/) for the icons used in the application.

---

