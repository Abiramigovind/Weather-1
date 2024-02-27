# Weather-1
### HTML:
- Sets up the basic structure of the webpage.
- Includes a form with an input field for searching by city name.
- Contains a main container with an empty div to display weather information.

### CSS (custom.css):
- Resets default styles for all elements.
- Styles the main container and input field for the search form.

### JavaScript (app.js):
- Defines the API key needed to access weather data.
- Selects necessary elements from the HTML document.
- Defines a function getWeather to fetch weather data from the OpenWeatherMap API.
- Defines a function showWeather to display the retrieved weather data.
- Listens for form submission and triggers the getWeather function with the city name entered by the user.

### Instructions:
1. Ensure you have an API key from OpenWeatherMap and replace API_KEY in your JavaScript code with your actual API key.
2. Host your custom CSS and JavaScript files alongside your HTML file.
3. When the HTML file is opened in a browser, users can search for a city by typing its name in the input field and pressing enter. The weather information for the entered city will be displayed below the search bar.
