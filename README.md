# Weather App (Flutter + BLoC/Cubit)

A clean and simple weather application built with Flutter. Users can search for a city to view current weather details. The UI adapts dynamically with gradient colors and condition-specific images.

## Features
- Current weather (temperature, max/min, condition description)
- City search with instant updates
- Dynamic theme gradient based on weather 
- Condition images from `assets/images`


## Tech Stack
- Flutter (Material)
- flutter_bloc (Cubit)
- http
- WeatherAPI.com (weather data API)


## Requirements
- Flutter SDK
- Dart SDK (bundled with Flutter)
- Editor (Android Studio / VS Code)
- WeatherAPI.com API key

## Setup
1) Install dependencies:
```bash
flutter pub get
```

2) Run the app:
```bash
flutter run
```

## Usage
- Launch the app to open `HomePage`.
- Tap the search icon in the AppBar.
- Enter a city name and submit (Enter / search icon).
- Weather data appears with adaptive background and image.

## Notes
- API endpoint: `http://api.weatherapi.com/v1/forecast.json` (7 days)
