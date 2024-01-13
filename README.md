# Weather App

A weather forecast application built with React.js that allows users to check the current weather details and a 5-day forecast for a selected city.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Environment Variables](#environment-variables)
- [Usage](#usage)
- [Live Demo](#live-demo)

## Features

1. **Current Weather Details:**
   - Current temperature
   - Minimum and maximum temperature
   - Humidity
   - Wind speed and direction
   - Description of the weather
   - Appropriate icon reflecting the current weather

2. **5-Day Forecast:**
   - Date
   - Average temperature
   - Description of the weather
   - Appropriate weather icon

3. **Unit Toggle Button:**
   - View weather details in both Celsius and Fahrenheit
    
4. **Responsive design for both desktop and mobile:**
 
5. **User-friendly interface with clear error handling( using react-toastify):**


## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repo.git
   
2. Change to the project directory:
 - cd your-repo
3. Install dependencies:
 - npm install
   
## Environment Variables
Create a .env file in the root folder and add the following variables:
- REACT_APP_API_KEY="your-api-key"
- REACT_APP_BASE_URL=https://api.openweathermap.org/data/
- Replace "your-api-key" with your OpenWeatherMap API key.

## Usage
- After setting up the environment variables, you can run the application:
- npm start
- Visit http://localhost:3000 in your browser to view the app.

## Live Demo
 [Live Demo of Weather App](https://harsh-yadav-weather-forecast.netlify.app/)


