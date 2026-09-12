# 🌾 Smart Agritech Dashboard

A lightweight web-based **Smart Agritech Dashboard** designed to provide useful agricultural information and farm-management tools through a single browser-based interface.

The application combines weather information, crop recommendations, yield estimation, market prices, fertilizer suggestions, and farm task management into one dashboard.

## ✨ Features

- 🌦️ **Weather Dashboard**
  - Displays current weather information using the OpenWeatherMap API.
  - Helps users access weather information for agricultural planning.

- 🌱 **Crop Recommendation**
  - Rule-based crop recommendation system.
  - Suggests suitable crops based on agricultural conditions.

- 🧮 **Yield Calculator**
  - Estimates crop yield using:
    `Acres × Kilograms per Acre`

- 💰 **Market Price**
  - Displays agricultural market price information.
  - Uses data from the Government of India's data.gov.in platform.

- 🧪 **Fertilizer Suggestions**
  - Provides rule-based fertilizer recommendations.

- 📋 **Farm Task Manager**
  - Helps organize and manage farm-related activities.

- 🌓 **Dark / Light Mode**
  - Allows users to switch between dark and light dashboard themes.

## 🛠️ Technology Stack

### Frontend
- HTML5
- CSS3
- JavaScript
- AngularJS 1.8.2

### APIs
- OpenWeatherMap API
- Government of India Data API — data.gov.in

### Architecture

The current application is implemented as a lightweight browser-based dashboard with the main application contained in:

`src/index.html`

## 📁 Project Structure

```text
Agritech-app/
├── public/
│   └── favicon.ico
├── src/
│   └── index.html
├── .gitignore
└── README.md
