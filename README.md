﻿# cautious-couscous
# WeatherApp

## Description
WeatherApp is a web application built using Django framework to provide users with real-time weather information. Users can search for weather forecasts by location and view details such as temperature, humidity, wind speed, and more.

## Features
- **Location-based Weather Forecast**: Users can search for weather forecasts by entering the name of a city or location.
- **Real-time Weather Data**: The application fetches and displays up-to-date weather information using reliable APIs.
- **Responsive Design**: The site is designed to be responsive, ensuring a seamless experience across various devices.
- **User-friendly Interface**: The interface is intuitive and easy to navigate, making it accessible to users of all levels.

## Installation
1. Clone the repository: `git clone https://github.com/kibeert/cautious-couscous.git`
2. Navigate to the project directory: `cd weatherapp`
3. Install dependencies: `pip install -r requirements.txt`
4. Set up environment variables:
   - Create a `.env` file in the root directory.
   - Add the following variables:
     ```
     SECRET_KEY=your_secret_key
     DEBUG=True
     ```
5. Run migrations: `python manage.py migrate`
6. Start the development server: `python manage.py runserver`

## Usage
1. Access the application through your web browser.
2. Enter the name of a city or location in the search bar and submit the form.
3. View the weather forecast for the specified location, including temperature, humidity, wind speed, and more.

## Technologies Used
- Django: Web framework for building the application.
- HTML/CSS: Frontend development for the user interface.
- Bootstrap: CSS framework for responsive design.
- OpenWeatherMap API: External API for fetching weather data.

## Contributing
Contributions are welcome! If you have any suggestions, bug fixes, or feature implementations, feel free to submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgements
Special thanks to the developers of Django and the OpenWeatherMap API for their valuable contributions to this project.
