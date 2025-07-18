﻿# Weather_API
A simple and elegant Weather Application built using HTML, CSS, and JavaScript.
It fetches real-time weather data using the WeatherAPI and displays the temperature, weather condition, and location details for any city entered by the user.

✅ Features
🌍 Search weather by city name.

🌡 Displays temperature in Celsius, weather condition, and an icon.

🖥 Clean and responsive UI with a centered input box.

⚠ Handles errors (invalid city names).

🔧 Technologies Used
HTML5 for structure

CSS3 for styling (gradient background, animations)

JavaScript (Fetch API) for making API calls

🔑 API Setup (Important)
To protect your API key, do not use the provided example key in this project.
Follow these steps:

Sign up on WeatherAPI.com and generate your own API key.

Go to the API Explorer section and check the current.json response.

Copy your API key and a sample API call response.

Paste them in the code:

Line 102: Replace YOUR_API_KEY_HERE with your API key.

Line 103: Replace the example API response call with your full API request URL.

javascript
Copy
Edit
const apiKey = "YOUR_API_KEY_HERE"; // Line 102
const url = `http://api.weatherapi.com/v1/current.json?key=${apiKey}&q=${location}&aqi=yes`; // Line 103
✅ This way, others won't use your API key when you upload the code.

📂 Project Structure
graphql
Copy
Edit
weather-app/
│
├── index.html      # Main HTML file (includes CSS & JS inline)
└── README.md       # Project documentation
