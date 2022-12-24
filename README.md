# Weather Detector

A simple Django web app that allows users to search for weather information by city name using the OpenWeatherMap API.

## Requirements

- Python 3.x
- Django 2.x

## Installation

1. Clone the repository:

```git clone https://github.com/<your-username>/weather-detector.git```

2. Navigate to the project directory:

```cd weather-detector```

3. Install the required packages:

```pip install -r requirements.txt```

4. Run the migrations to set up the database:

```python manage.py migrate```

5. Run the development server:

```python manage.py runserver```

6. Open a browser and go to http://127.0.0.1:8000 to use the app.

## Usage

1. Enter the name of a city in the search field and click the search button.

2. The app will display the country code, coordinates, temperature, pressure, and humidity for the specified city.

## Files

- `index.html` contains the HTML code for the app's user interface.

- `views.py` contains the view function that handles the weather search and displays the data to the user.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.