# weather dashboard

## meaning
this is a small react app that shows current weather and 5 day forecast for any city. it uses a search bar, weather cards, and a weather api service.

## features
- search city weather
- show current temperature, humidity, wind
- show 5 day forecast
- clean ui with separate components
- api calls written in one service file

## project structure
weather-dashboard/
│
├── public/
│   ├── index.html
│   └── favicon.ico
│
├── src/
│   ├── components/
│   │   ├── SearchBar.jsx
│   │   ├── SearchBar.css
│   │   ├── WeatherCard.jsx
│   │   ├── WeatherCard.css
│   │   ├── ForecastCard.jsx
│   │   └── ForecastCard.css
│   │
│   ├── services/
│   │   └── weatherService.js
│   │
│   ├── App.jsx
│   ├── App.css
│   ├── index.js
│   └── index.css
│
├── .gitignore
├── package.json
├── package-lock.json
└── README.md

## how to run
1. install node
2. install packages  
3. start project  

## api used
openweathermap api  
endpoint stores in `weatherService.js`

## simple example
you type "delhi" in search, api fetches delhi weather, app shows temperature and forecast.
