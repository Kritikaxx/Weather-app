## *Weather Dashboard*🌤️

A responsive weather web app built with React.js that provides real-time weather information for any city worldwide. Includes light/dark theme toggle and elegant UI.

![Weather Dashboard Screenshot]("C:\Users\KIIT\OneDrive\Pictures\Screenshots\Screenshot 2025-04-09 060923.png")("C:\Users\KIIT\OneDrive\Pictures\Screenshots\Screenshot 2025-04-09 061006.png")

## Features:
## -Core Features
-**City Search**: Get current weather by searching any city
-Weather Details:
  - Temperature (°C)
  - Weather Condition & Icon
  - Humidity (%)
  - Wind Speed (km/h)
  - Location Name
- **Error Handling**:
  - Invalid city alerts
  - API error handling
- **Loading States**: Animated spinner during data fetch
- **Responsive Design**: Works on mobile & desktop

### Bonus Features Implemented:
- **Theme Toggle**: Switch between light/dark modes
- **CSS Animations**:
  - Smooth theme transitions
  - Loading spinner animation
- **Auto-search**: Default location (Delhi) on initial load
- **Optimized UI**:
  - Gradient backgrounds
  - Modern card design
  - Interactive elements

## Tech Stack:
-Framework: React.js (Vite)
-Styling: Vanilla CSS with modern flexbox/grid
-API: OpenWeatherMap Current Weather Data
-Build Tool: Vite
-Deployment: Vercel/Netlify

## Setup Instructions:
### Prerequisites
- Node.js (v16+)
- npm (v8+)

### Installation
1. Clone repository:
    git clone [your-repo-url]
    cd weather-dashboard

2. Install dependencies:
    npm install

3. Add API Key:
- Create `.env` file in root directory
    VITE_API_KEY=your_openweather_api_key

4. Run locally:
npm run dev

## API Integration:
-API Used: OpenWeatherMap Current Weather Data
-Rate Limit: 60 calls/minute (free tier)
-Key Management: Stored in environment variables

## Deployment:
1. Build for production:
    npm run build

2. Deploy to:
[![Deploy with Vercel](https://weather-app-nine-xi-10.vercel.app/)]

## Future Enhancements:
- 5-day weather forecast
- Search history
- Unit conversion (C/F)
- Geolocation support
- Air quality index



