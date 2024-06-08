# Weather App

A weather application that allows users to search for cities and view current weather information, including local time, temperatures, humidity, wind speed and direction, sunrise and sunset times. Users can switch between metric and imperial units. The application handles errors gracefully and provides loading indicators when fetching data.

## Features

- **Search Cities**: Users can search for cities to get weather information.
- **Current Local Time and Date**: Displays the current local time and date for the selected city.
- **Temperatures and Humidity**: Shows current temperature, humidity, and daily min/max temperatures.
- **Wind Speed and Direction**: Displays current wind speed and direction in both metric (m/s) and imperial (miles/hour) units.
- **Sunrise and Sunset Times**: Shows the times for sunrise and sunset in the selected city.
- **Metric vs Imperial System**: Allows users to switch between metric (Celsius, meters per second) and imperial (Fahrenheit, miles per hour) systems.
- **Error Handling and Loading Info**: Gracefully handles errors such as city not found and API errors. Provides loading indicators while fetching data.

## Installation

Follow these steps to install and run the application:

1. Clone the repository:

   ```bash
   git clone https://github.com/madzadev/weather-app.git
   cd weather-app
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Log in to OpenWeatherMap and create an API key:
   - Sign up or log in to [OpenWeatherMap](https://openweathermap.org/).
   - Navigate to your account and find the API keys section.
   - Generate a new API key.

4. Set up environment variables:
   - Copy the example environment file:

     ```bash
     cp .env .env
     ```

   - Open `.env` and paste your OpenWeatherMap API key:

     ```plaintext
     OPENWEATHER_API_KEY=your_api_key_here
     ```

5. Start the development server:

   ```bash
   npm run dev
   ```

6. Open your browser and navigate to `http://localhost:3000` to view the application.

## Usage

- Enter a city name in the search bar and press Enter or click the search button to get weather information for that city.
- Use the toggle button to switch between metric and imperial units.
- The application will display the weather information including current weather, daily forecast, and other relevant information based on the selected city.

## Built With

- [React](https://reactjs.org/) - JavaScript library for building user interfaces
- [Next.js](https://nextjs.org/) - React framework for building server-side rendered applications
- [OpenWeatherMap API](https://openweathermap.org/api) - Weather data API


