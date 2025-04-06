# WeatherProject

WeatherProject is a Django-based web application that provides real-time weather information for any city. Leveraging the OpenWeatherMap API, the application offers current weather data, including temperature, humidity, wind speed, and weather conditions.

## Features

- **Real-Time Weather Data**: Obtain up-to-date weather information for any city worldwide.
- **User-Friendly Interface**: Easily navigate through the application to access weather details.
- **City Search Functionality**: Search for weather information by entering the desired city name.

## Technologies Used

- **Backend**: Python with Django framework.
- **API Integration**: OpenWeatherMap API for fetching weather data.
- **Frontend**: HTML, CSS, and Bootstrap for responsive design.

## Setup and Installation

To set up the WeatherProject on your local machine, follow these steps:

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/Monishj1105/weather.git
   ```


2. **Navigate to the Project Directory**:

   ```bash
   cd weather/weatherproject
   ```


3. **Create and Activate a Virtual Environment**:

   ```bash
   python3 -m venv env
   source env/bin/activate  # On Windows, use 'env\Scripts\activate'
   ```


4. **Install Required Dependencies**:

   ```bash
   pip install -r requirements.txt
   ```


5. **Set Up OpenWeatherMap API Key**:

   - Sign up at [OpenWeatherMap](https://openweathermap.org/api) to obtain an API key.
   - In the project directory, create a `.env` file and add your API key:

     ```
     OPENWEATHERMAP_API_KEY='your_api_key_here'
     ```

6. **Apply Database Migrations**:

   ```bash
   python manage.py migrate
   ```


7. **Run the Development Server**:

   ```bash
   python manage.py runserver
   ```


8. **Access the Application**:

   Open your web browser and navigate to `http://127.0.0.1:8000/` to view the application.

## Usage

- **Search Weather by City**: Enter the name of any city in the search bar to retrieve current weather information.
- **View Weather Details**: The application displays temperature, humidity, wind speed, and weather conditions for the searched city.

## Contributions

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The application utilizes the [OpenWeatherMap API](https://openweathermap.org/api) for weather data.
- Special thanks to the contributors and the open-source community for their support. 
