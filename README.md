# Weather Application

This is a simple weather application that fetches real-time weather data from the OpenWeatherMap API and displays it on the webpage. Users can search for weather information by entering the name of a city. The application provides a clean and intuitive interface for users to quickly access weather updates.

## Features

- **Real-time Weather Data**: Fetches weather data from the OpenWeatherMap API, ensuring the displayed information is up-to-date.
- **Dynamic Backgrounds**: Changes the background image based on the searched city, providing a visually appealing experience.
- **Detailed Weather Information**: Displays essential weather details such as temperature, humidity, wind speed, and weather description.
- **Search Functionality**: Allows users to search for weather information by entering the name of a city.
- **Responsive Design**: Ensures the application works well across various devices and screen sizes.

## Usage

To use the application:
1. Enter the name of a city in the search bar.
2. Press the search button or hit Enter.
3. The weather information for the specified city will be displayed on the webpage, along with a background image reflecting the weather conditions.

## How to Run

To run the application:
1. Download or clone the repository.
2. Open the `index.html` file in a web browser.

## Dependencies

This application relies on the following dependencies:
- **Fetch API**: Used for making HTTP requests to the OpenWeatherMap API.
- **OpenWeatherMap API**: Provides weather data for various locations.
- **Unsplash API**: Fetches background images based on the searched city to enhance the visual experience.

## Notes

- The weather data is fetched in metric units, with temperature displayed in Celsius and wind speed in kilometers per hour.
- In case the entered city name does not return any weather data, the application alerts the user accordingly.
- This application does not require any server-side code and can be run entirely on the client-side.

