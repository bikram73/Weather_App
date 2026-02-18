# Weather App - Weatherstack Demo

A modern, responsive weather dashboard built with vanilla HTML, CSS, and JavaScript. This application leverages the [Weatherstack API](https://weatherstack.com/) to provide real-time, historical, and marine weather data in a sleek glassmorphism interface.

## Features

-   **Current Weather**: Get up-to-date temperature, feels-like, humidity, wind speed, and weather descriptions.
-   **Historical Data**: Look up weather conditions for specific past dates.
-   **Marine Weather**: Access ocean data including swell height, wave period, and wind conditions.
-   **Smart Search**: Location autocomplete suggestions as you type.
-   **Geolocation**: Automatically detects your current location (requires browser permission).
-   **Unit Conversion**: Support for Metric (Celsius, km/h), Imperial (Fahrenheit, mph), and Scientific (Kelvin, m/s) units.
-   **Raw Data View**: Option to inspect the raw JSON response from the API for debugging.

## Setup & Usage

1.  **Download**: Save the `index.html` file to your computer.
2.  **Open**: Double-click `index.html` to open it in any modern web browser (Chrome, Firefox, Edge, Safari).

## Configuration

To ensure the app works consistently, you should use your own API key from Weatherstack.

1.  Sign up for a free API key at weatherstack.com.
2.  Open `index.html` in a text editor (Notepad, VS Code, etc.).
3.  Find the `API_KEY` constant near the top of the `<script>` tag:

    ```javascript
    const API_KEY = 'YOUR_API_KEY_HERE';
    ```

4.  Replace the existing key with your new API key.
5.  Save the file and refresh your browser.

## Technologies

-   **HTML5**: Semantic structure.
-   **CSS3**: Custom variables, Grid/Flexbox layout, and Glassmorphism styling.
-   **JavaScript (ES6+)**: Async/Await for API fetching, DOM manipulation.

## License

This project is open source and available for personal and educational use.