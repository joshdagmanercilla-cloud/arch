# Weather Atlas

A responsive weather dashboard with live current conditions, an hourly forecast, and a seven-day outlook. Weather data and location search are powered by the public [Open-Meteo API](https://open-meteo.com/); no API key is required.

## Run locally

Open `index.html` in a browser, or serve this repository with a static web server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000` on the same computer.

## Features

- Search cities and places with location suggestions.
- Optional browser geolocation (requires permission and a secure context such as HTTPS or localhost).
- Current temperature, apparent temperature, humidity, wind, UV index, and daily high/low.
- 24-hour and seven-day forecasts.
- Celsius/Fahrenheit and km/h/mph display options.
- Responsive layout, loading/error states, and reduced-motion support.

## Publish on GitHub Pages

In the repository settings, enable GitHub Pages and configure deployment from the `main` branch and repository root. Once deployment completes, GitHub Pages displays the public website URL in the Pages settings.

The dashboard calls Open-Meteo directly from the browser. Forecast availability depends on the public API and the user's network connection.
