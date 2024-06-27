# weatherAPI-assignment


## Weather API to HTML Card Assignment
Objective
Create a web application that fetches weather data from a weather API and displays it in a user-friendly HTML card format. This assignment aims to help you understand how to work with APIs, manipulate the DOM with JavaScript, and style content with CSS.

## Requirements
Fetch Weather Data: Use a weather API (e.g., OpenWeatherMap, Weatherstack) to get weather information based on user input.
User Input: Allow the user to input a city name to retrieve weather data.
Display Data: Show the weather data in a styled HTML card.
Responsive Design: Ensure the weather card is responsive and looks good on both desktop and mobile devices.
Error Handling: Handle errors gracefully, such as when the API request fails or the city is not found.
## Getting Started
Prerequisites
Basic knowledge of HTML, CSS, and JavaScript.
An API key from the weather service you plan to use (e.g., OpenWeatherMap API key).

Use the following HTML layout 
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Weather Card</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="weather-app">
    <input type="text" id="cityInput" placeholder="Enter city name">
    <button id="getWeatherBtn">Get Weather</button>
    <div class="weather-card" id="weatherCard">
      <!-- Weather data will be displayed here -->
    </div>
  </div>
  <script src="script.js"></script>
</body>
</html>
```

The HTML card needs to have the 
- City Title 
- Current Temperature and information 
- Display the weeks Temperature and and information 


# Instructions
## Fork the Repository:

Go to the repository on GitHub.
Click on the "Fork" button at the top right of the repository page to create a copy of the repository under your GitHub account.
Clone the Repository:

Clone the forked repository to your local machine using the following command:
bash
Copy code
```
git clone https://github.com/your-username/weatherAPI-assignment.git
cd weatherAPI-assignment
```
