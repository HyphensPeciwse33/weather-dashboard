# 🌤️ Weather Dashboard

A beautiful, responsive weather dashboard that fetches real-time weather data from the OpenWeatherMap API.

## Features

- ✅ Real-time weather updates
- ✅ Current weather conditions (temperature, humidity, wind speed, feels like)
- ✅ 5-day weather forecast
- ✅ Search functionality for any city
- ✅ Responsive design (mobile & desktop)
- ✅ Beautiful gradient UI with smooth animations

## Demo

Visit the live dashboard: [Weather Dashboard](https://HyphensPeciwse33.github.io/weather-dashboard/)

## Setup Instructions

### 1. Get an API Key
1. Visit [OpenWeatherMap](https://openweathermap.org/api)
2. Sign up for a free account
3. Go to "API keys" section
4. Copy your API key

### 2. Configure the API Key
Open `script.js` and replace `YOUR_API_KEY_HERE` with your actual API key:

```javascript
const API_KEY = 'your-api-key-here';
```

### 3. Run Locally
Simply open `index.html` in your browser, or use a local server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (with http-server)
npx http-server
```

Then navigate to `http://localhost:8000`

## File Structure

```
weather-dashboard/
├── index.html      # HTML structure
├── styles.css      # CSS styling
├── script.js       # JavaScript functionality
└── README.md       # Documentation
```

## Technologies Used

- **HTML5** - Structure
- **CSS3** - Styling with gradients and animations
- **JavaScript (Vanilla)** - API integration and DOM manipulation
- **OpenWeatherMap API** - Weather data

## Features Explained

### Search Functionality
- Search for any city in the world
- Press Enter or click the Search button
- Real-time validation with error handling

### Current Weather Display
- Temperature
- Weather description
- Humidity percentage
- Wind speed
- "Feels like" temperature

### 5-Day Forecast
- Daily forecast cards
- Temperature predictions
- Weather conditions
- Hover effects for better UX

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## API Rate Limits

The free OpenWeatherMap API has rate limits:
- 1,000 calls/day
- 60 calls/minute

## Future Enhancements

- [ ] Geolocation support
- [ ] Temperature unit toggle (°C/°F)
- [ ] Weather alerts
- [ ] Historical weather data
- [ ] Multiple city comparison
- [ ] Dark mode
- [ ] PWA support

## License

MIT License - Feel free to use this project as you wish!

## Credits

- Weather data: [OpenWeatherMap](https://openweathermap.org/)
- Icons: Built-in emoji
- Inspiration: Modern weather dashboards

---

**Made with ❤️ by HyphensPeciwse33**
