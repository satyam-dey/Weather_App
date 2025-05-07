🌦️ Weather App
  - A sleek and responsive Weather App built with React, Vite, and Tailwind CSS. This application fetches real-time weather data for any city worldwide using the OpenWeatherMap API, providing users with current weather conditions in a user-friendly interface.

🚀 Features
  - Real-Time Weather Data: Fetches and displays current weather information for any city.

  - Responsive Design: Ensures optimal viewing experience across various devices.

  - Search Functionality: Allows users to search for weather details by city name.

  - Clean UI: Utilizes Tailwind CSS for a modern and clean user interface.

🛠️ Technologies Used
  - React: JavaScript library for building user interfaces.

  - Vite: Next-generation frontend tooling for faster and leaner development.

  - Tailwind CSS: Utility-first CSS framework for rapid UI development.

  - OpenWeatherMap API: Provides weather data for locations worldwide.

⚙️ Getting Started
  Follow these steps to set up and run the project locally:

  - Prerequisites
    Node.js installed on your machine.

  - An API key from OpenWeatherMap.

  - Installation
    Clone the repository:
  
        git clone https://github.com/satyam-dey/Weather_App.git
        cd Weather_App
  - Install dependencies:

        npm install
  - Configure Environment Variables:
  - Create a .env file in the root directory and add your OpenWeatherMap API key:

        VITE_API_KEY=your_openweathermap_api_key
  - Start the development server:

        npm run dev
  - The application will be available at http://localhost:5173.

📁 Project Structure
  
    Weather_App/
    ├── public/
    │   └── weather.png
    ├── src/
    │   ├── assets/
    │   │   ├── icons
    │   │   └── images
    │   ├── components/
    │   │   ├── BackgroundLayout.jsx
    │   │   ├── index.jsx
    │   │   ├── MiniCard.jsx
    │   │   └── WeatherCard.jsx
    │   ├── context/
    │   │   └── useDate.jsx
    │   ├── utils/
    │   ├── App.jsx
    │   ├── App.css
    │   ├── index.css
    │   └── main.jsx
    ├── .env
    ├── .gitignore
    ├── index.html
    ├── eslint.config.js
    ├── package.json
    ├── package-lock.json
    ├── postcss.config.js
    ├── README.md
    ├── style.css
    ├── tailwind.config.js
    └── vite.config.js

🙋‍♂️ Author
  - Satyam Dey - GitHub Profile
