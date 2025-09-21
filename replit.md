# Smart Outfit Suggestor

## Overview
A Flask-based web application that provides personalized outfit recommendations based on real-time weather data. Users enter their city, and the app fetches weather information to suggest appropriate clothing.

## Project Architecture
- **Backend**: Flask web framework with Python
- **Frontend**: HTML templates with CSS styling and JavaScript theme switching
- **API Integration**: wttr.in weather service for real-time weather data
- **Deployment**: Configured for autoscale deployment with gunicorn

## Key Features
- Real-time weather data fetching
- Smart outfit recommendations based on temperature
- Beautiful glass-morphism UI design
- Multiple theme options (Purple, Cherry, Ocean)
- Responsive design

## Project Structure
```
/
├── app.py                 # Main Flask application
├── templates/
│   └── index.html        # Main template
├── static/
│   └── style.css         # Styling and themes
├── requirements.txt      # Python dependencies
├── Procfile             # For deployment
└── vercel.json          # Original Vercel config
```

## Current Status
- ✅ Flask app configured and running on port 5000
- ✅ Templates and static files properly organized
- ✅ Weather API integration working
- ✅ Deployment configuration completed
- ✅ Development workflow set up

## Recent Changes (2025-09-21)
- Successfully imported from GitHub
- Set up proper Flask directory structure
- Configured app to run on 0.0.0.0:5000 for Replit environment
- Fixed weather API to use dynamic city input instead of hardcoded "pune"
- Set up development workflow
- Configured deployment settings for production

## Dependencies
- Flask>=2.2.5
- requests>=2.32.0  
- gunicorn>=21.2.0
- python-dotenv>=1.0.1

## Development
The app runs in debug mode with auto-reload enabled. The main workflow "Flask App" serves the application on port 5000.

## Deployment
Configured for autoscale deployment using gunicorn server binding to 0.0.0.0:5000 with reuse-port enabled.