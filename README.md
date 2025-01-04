# Weather-App
Our Weather App is a user-friendly, real-time application that allows users to check the current weather conditions for any city around the world. Built using Django, HTML, and CSS, the app leverages the power of web technologies to fetch weather data from external APIs and present it in a clean, interactive, and visually appealing interface.

Technology Stack:

Django (Python):
The backend is powered by Django, a powerful web framework for Python. Django handles requests from users, interacts with weather APIs, and serves the weather data in a structured format. It also manages routing and templating to render dynamic pages.
HTML:
The structure of the app is created with HTML (HyperText Markup Language). HTML provides the foundation for displaying content, including the weather data, input fields, and buttons.
CSS:
The app uses CSS (Cascading Style Sheets) to apply visual styles. From the color palette to the layout of elements, CSS enhances the user experience, making the interface not only functional but also attractive.


How It Works:

User Interaction:
Users enter the name of a city into the search bar and click the "Get Weather" button.
Django Backend:
Upon submission, the form data (city name) is sent to the Django backend, which handles the request.
Django makes an API call to a weather service (e.g., OpenWeatherMap API) to retrieve current weather data for the city.
Data Display:
The backend processes the API response and extracts relevant information like temperature, weather condition, humidity, and wind speed.
This data is then passed to the frontend, where Django's templating engine renders it within the HTML structure.
CSS Styling:
The weather data is displayed on a visually appealing page, styled using CSS to ensure readability, clarity, and responsiveness across all devices.


Technologies Used:

Django for backend logic, form handling, and interacting with APIs.
HTML5 for structuring the content of the web pages.
CSS3 for styling the app and ensuring a responsive, user-friendly interface.
External Weather API (such as OpenWeatherMap or WeatherAPI) to fetch real-time weather data.
