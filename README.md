# Django Weather App

This is a simple Django web application that provides weather information based on user input. It utilizes a weather API to fetch real-time weather data.

## Features

- User-friendly interface for entering location details
- Displays current weather conditions, temperature, and other relevant information
- Responsive design for a seamless experience on different devices

## Installation

1. Clone the repository:

   ```bash git clone https://github.com/your-username/Django-Weather-App.git ```

2. Navigate to the project directory:

   ```bash cd Django-Weather-App ```
   
3. Install the required dependencies:
   
   ```bash pip install -r requirements.txt ```

4. Apply database migrations:

  ```bash python manage.py migrate ```
  
5. Run the development server:

  ```bash python manage.py runserver ```
The app will be accessible at http://127.0.0.1:8000/.

Configuration
Open weatherapp/settings.py and add your API key in the WEATHER_API_KEY variable.
Usage
Access the application in your web browser.
Enter the location details (e.g., city name) in the provided form.
Click the "Get Weather" button to fetch and display the weather information.
Screenshots
Include screenshots or GIFs to showcase the application's functionality.

Technologies Used
Django
HTML
CSS
Weather API (mention the specific API you are using)
Contributing
If you'd like to contribute to this project, please follow these guidelines.

Fork the repository.
Create a new branch: 

```bash
git checkout -b feature/your-feature-name
```
Commit your changes: 
```bash 
git commit -m 'Add new feature' 
```

Push to the branch: 
```bash 
git push origin feature/your-feature-name
```
Submit a pull request.
