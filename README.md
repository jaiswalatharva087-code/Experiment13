 Weather Forecast App

A responsive React application providing real-time weather metrics and dynamic 5-day temperature visualizations powered by OpenWeather API and Chart.js.

📌 Features

Real-Time Weather Data: Fetch current conditions including temperature, "feels like" temp, humidity, pressure, and wind speed for any city worldwide.

5-Day Interactive Trend Chart: Visualize temperature variations across 3-hour intervals using dynamic Chart.js line plots.

Environment Variable Support: Keep API secrets safe with local .env configuration.

Modular Architecture: Component-driven design separated cleanly between state management, layout, and data visualization.

🛠️ Tech Stack

Frontend: React.js

Data Fetching: Axios

Visualization: Chart.js & react-chartjs-2

API Service: OpenWeatherMap API (/weather & /forecast endpoints)

📂 Project Structure

├── public/
├── src/
│   ├── App.js            # Main application layout container
│   ├── Weather.js        # Weather search logic & state handler
│   ├── WeatherChart.js   # 5-day forecast visualization component
│   └── index.js          # Entry point
├── .env.example          # Environment variables template
├── .gitignore            # Git exclusion rules
├── package.json          # Dependency configurations
└── README.md             # Project documentation


🚀 Getting Started

Follow these steps to get a local copy up and running.

1. Prerequisites

Make sure you have Node.js and npm installed on your machine:

Node.js (v14.0 or higher recommended)

npm or yarn

2. Get an API Key

Register for a free account at OpenWeatherMap.

Navigate to your API keys page and generate a standard API key.

3. Installation

Clone the repository to your local machine:

git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name


Install the project dependencies:

npm install


4. Environment Setup

Create a .env file in the root directory of the project:

cp .env.example .env


Open .env and add your OpenWeather API key:

REACT_APP_OPENWEATHER_API_KEY=your_openweather_api_key_here


Note: Ensure .env is added to your .gitignore so your API key isn't committed publicly.

🏃 Running the Application

To launch the development server:

npm start


Runs the app in development mode. Open http://localhost:3000 to view it in your browser.

📜 Available Scripts

In the project directory, you can run:

npm start: Runs the app in development mode.

npm test: Launches the test runner in interactive watch mode.

npm run build: Builds the app for production to the build folder.

🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

Fork the Project

Create your Feature Branch (git checkout -b feature/AmazingFeature)

Commit your Changes (git commit -m 'Add some AmazingFeature')

Push to the Branch (git push origin feature/AmazingFeature)

Open a Pull Request

📄 License

Distributed under the MIT License. See LICENSE for more information.
