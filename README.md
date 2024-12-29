NAME:M PRAVEENKUMAR
PROJECT: WEATHER FORECAST APP

Explanation of the Code

This code represents a simple Weather Forecast App that fetches and displays weather information for a given city using the OpenWeatherMap API.

HTML Structure:

1. DOCTYPE & HTML Tag: Declares the document type and sets the language of the page to English (lang="en").


2. Head Section:

Meta Tags: Specifies the character set (UTF-8) and the viewport settings for responsive design.

Title: The title of the webpage is set to "Weather Forecast App".

Styles: The CSS styles are applied to ensure the design is visually appealing and user-friendly. It includes general styles, input field styling, button hover effects, and weather information display styles.



3. Body Section:

Container: A central white box that holds the entire content, styled with a background, padding, and rounded corners.

Weather Info: Displays a title, an input field where the user can enter the city name, and a button to initiate the weather fetch.

Weather Info Div: This area will hold the weather details fetched from the API.




JavaScript Functionality:

1. API Key: You need to replace 'your_api_key_here' with an actual API key from OpenWeatherMap (sign up on their site to get one).


2. Event Listener: When the "Get Weather" button is clicked, the script checks if the user has entered a city name.


3. API Request: If the city is provided, it constructs a URL using the city name and the API key, then sends a request to the OpenWeatherMap API.


4. Fetching Weather Data: The fetch() function sends a request to OpenWeatherMap. If the city is found, it returns the weather details (e.g., temperature, weather description, humidity, wind speed) in JSON format.


5. Display Data: Upon successful fetch, the data is displayed inside the .weather-info div using HTML and the weather icon is fetched from the OpenWeatherMap server.


6. Error Handling: If an error occurs (such as the city not being found), an alert is displayed with the error message.



CSS Styling:

Body Styling: A gradient background is applied, and Flexbox is used to center the content both vertically and horizontally.

Container: The weather display area has a white background with padding, rounded corners, and a shadow for a card-like appearance.

Buttons & Inputs: Styled with padding, rounded corners, and transitions for hover effects.

Weather Information: Weather data (temperature, humidity, etc.) is displayed with specific font styling and the weather icon is also shown.


Project Name:

Weather Forecast App
