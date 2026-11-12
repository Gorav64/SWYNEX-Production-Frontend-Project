# SWYNEX Task 4 — AeroCast Production Frontend Project

AeroCast is a responsive live weather dashboard built with HTML5, CSS3 and vanilla JavaScript. It integrates the Open-Meteo Geocoding and Forecast APIs.

## Features
- Search worldwide cities and choose matching locations
- Current weather, six-hour outlook and seven-day forecast
- Highlights: feels-like temperature, humidity, wind, rain chance, UV index and sunrise/sunset
- Celsius/Fahrenheit toggle
- Optional browser geolocation (permission-based)
- Save up to six favourite locations
- Last selected location and preferences saved locally
- Loading state, request timeout, network/API error handling and empty search state
- Responsive desktop, tablet and mobile layout
- Accessible labels and live status messages

## APIs
- Geocoding: https://geocoding-api.open-meteo.com/v1/search
- Forecast: https://api.open-meteo.com/v1/forecast
- Official documentation: https://open-meteo.com/en/docs

The public Open-Meteo API does not require an API key for non-commercial use. Review current terms and attribution requirements before commercial use.

## Run locally
1. Download or clone the repository.
2. Open the folder in VS Code.
3. Run `index.html` with VS Code Live Server or another local static server.
4. Search for a city and test the unit toggle, favourites and location button.

A local server is recommended, especially when testing browser geolocation.

## Files
- `index.html` — semantic page structure
- `style.css` — responsive styling and layout
- `script.js` — API requests, reusable rendering functions, state and error handling
- `README.md` — project documentation
- `DEPLOYMENT_GUIDE.md` — GitHub, hosting and submission steps

## Technology
HTML5 · CSS3 · JavaScript ES6+ · Fetch API · Open-Meteo APIs · LocalStorage · Geolocation API

## Important
This is a frontend project. Saved favourites and the last location stay in the visitor's browser; there is no backend account or cross-device sync.
