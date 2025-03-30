# 🌦 Weather Forecast - Your Personal Weather Assistant
<div align="center">
  <img src="./demo.gif" alt="Weather Forecast Banner" height="300" width="500" />
</div>

## 🌟 Overview
Weather Forecast is a powerful, user-friendly application that provides real-time weather information at your fingertips. Designed for weather enthusiasts and everyday users alike, our app delivers accurate, up-to-date forecasts for any city worldwide through seamless integration with the OpenWeatherMap API.

## ✨ Features
### 🔍 City Search
- Intuitive search functionality for any city globally
- Instant results with real-time API integration
- Recent search history tracking

### 🌡 Comprehensive Weather Data
- Current temperature in Celsius
- Weather conditions with visual indicators
- Humidity percentage tracking
- Wind speed monitoring in km/h
- Dynamic weather icons based on conditions

### 📊 Extended Functionality
- 5-Day weather forecast for planning ahead
- User-friendly loading states during data fetching
- Elegant error handling for invalid searches
- Dark/Light theme toggle for personalized viewing

### 💻 Responsive Design
- Seamless experience across all devices
- Optimized layouts for mobile and desktop
- Clean, modern user interface
- Smooth animations and transitions

## 🛠 Technical Stack
- React.js
- Tailwind CSS / MUI / Chakra UI / Styled Components
- OpenWeatherMap API
- Axios/Fetch for API requests
- Framer Motion (optional)

## 📋 Prerequisites
- Node.js (v14 or higher)
- NPM or Yarn
- OpenWeatherMap API key

## 🚀 Getting Started
1. Clone the repository:
bash
git clone https://github.com/AnupriyaSingh04/Weather-Forcast.git
cd Weather-Forcast


2. Install dependencies:
bash
npm install
# or
yarn install


3. Set up environment variables:
bash
cp .env.example .env
# Add your OpenWeatherMap API key to .env


4. Start the development server:
bash
npm run dev
# or
yarn start

Tech Stack to Use:

React.js - As required in your assignment for the frontend framework

You can use Create React App (CRA), Vite, or Next.js as the project starter


State Management

React Hooks (useState, useEffect, useContext) as mentioned in your requirements


Styling Options (choose one)

Tailwind CSS (recommended for rapid development and responsive design)
Material UI (MUI)
Chakra UI
Styled Components


API Integration

Axios or Fetch API for making requests to OpenWeatherMap
OpenWeatherMap API endpoints 

## 🔑 API Key Setup
The app requires an OpenWeatherMap API key:
1. Register at [OpenWeatherMap](https://openweathermap.org/api)
2. Generate a free API key
3. Add it to your .env file:
env
REACT_APP_OPENWEATHER_API_KEY=your_api_key_here

Primary Endpoints

Current Weather Data

URL: https://api.openweathermap.org/data/2.5/weather?q={city}&appid={API_KEY}&units=metric
Returns: Current temperature, humidity, wind speed, weather condition, etc.
Rate Limits

Free Plan Limitations:

60 calls per minute (1,000 calls per day)
Sufficient for development and small-scale deployment
No credit card required


Implementation Best Practices:

Add debouncing to search inputs (300-500ms) to prevent excessive API calls
Cache previous search results locally (localStorage)
Display last searched city on app load to reduce API calls

Error Handling

Common HTTP Status Codes:

401: Invalid API key
404: City not found

## 📱 Responsive Design
- Mobile-first approach
- Desktop optimization
- Tablet-friendly interface


## 🎯 Bonus Features
- Recent search history (last 5 cities)
- 5-Day/3-Hour forecast display
- Dark/Light theme toggle
- Refresh button functionality
- Loading animations
- Smooth transitions between states

## 🤝 Contributing
We welcome contributions! Please follow these steps:
1. Fork the repository
2. Create your feature branch (git checkout -b feature/AmazingFeature)
3. Commit your changes (git commit -m 'Add some AmazingFeature')
4. Push to the branch (git push origin feature/AmazingFeature)
5. Open a Pull Request

## 📄 License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## 🙏 Acknowledgments
- OpenWeatherMap for their comprehensive API
- React.js community
- All contributors to this project

## 📞 Support
Having issues? Let us know!
- 🐛 [Submit a bug report](https://github.com/AnupriyaSingh04/Weather-Forcast/issues)
- 💡 [Request a feature](https://github.com/AnupriyaSingh04/Weather-Forcast/issues)
- 📧 Email at: anupriyasingh534@gmail.com
  
---
<div align="center">
  Made with ❤ by Anupriya Singh
</div>
