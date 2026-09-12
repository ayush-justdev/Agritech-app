# 🌾 Smart Agritech Dashboard

> **A lightweight web-based agricultural dashboard that brings weather insights, crop recommendations, yield estimation, market prices, fertilizer suggestions, and farm task management into one simple interface.**

The **Smart Agritech Dashboard** is a browser-based agricultural assistance application designed to provide farmers and agriculture learners with useful information and practical farm-management tools from a single dashboard.

The project focuses on combining multiple agricultural utilities into a **simple, accessible, and responsive web interface** using core web technologies.

---

## ✨ Features

### 🌦️ Weather Dashboard

* Displays current weather information using the **OpenWeatherMap API**.
* Provides weather information useful for agricultural planning.
* Simple and easy-to-understand weather interface.

### 🌱 Crop Recommendation

* Uses a **rule-based recommendation system**.
* Suggests suitable crops according to selected agricultural conditions.
* Designed as a lightweight decision-support feature.

### 🧮 Yield Calculator

Estimate expected crop production using:

```text
Estimated Yield = Acres × Kilograms per Acre
```

Provides a quick way to estimate potential agricultural output.

### 💰 Market Price

* Displays agricultural market-price information.
* Uses data provided through the **Government of India's data.gov.in platform**.
* Helps users access relevant market information from the dashboard.

### 🧪 Fertilizer Suggestions

* Provides rule-based fertilizer recommendations.
* Helps connect crop-related conditions with basic fertilizer guidance.

### 📋 Farm Task Manager

* Allows users to organize farm-related activities.
* Provides a simple way to keep track of agricultural tasks.

### 🌓 Dark / Light Mode

* Supports both dark and light dashboard themes.
* Improves usability across different lighting conditions.

---

## 🛠️ Technology Stack

| Technology             | Usage                              |
| ---------------------- | ---------------------------------- |
| **HTML5**              | Application structure              |
| **CSS3**               | Styling and responsive interface   |
| **JavaScript**         | Application logic and interactions |
| **AngularJS 1.8.2**    | Frontend framework                 |
| **OpenWeatherMap API** | Weather information                |
| **data.gov.in API**    | Agricultural market-price data     |

---

## 🏗️ Application Architecture

The application follows a lightweight browser-based architecture:

```text
              ┌─────────────────────────┐
              │        User             │
              └────────────┬────────────┘
                           │
                           ▼
              ┌─────────────────────────┐
              │   Smart Agritech UI     │
              │  HTML + CSS + AngularJS │
              └────────────┬────────────┘
                           │
             ┌─────────────┼─────────────┐
             ▼             ▼             ▼
        Weather API   Market API    Local Logic
        OpenWeather    data.gov.in   Recommendations
             │             │             │
             └─────────────┼─────────────┘
                           ▼
              ┌─────────────────────────┐
              │ Agricultural Dashboard  │
              └─────────────────────────┘
```

The primary application is contained in:

```text
src/index.html
```

---

## 📁 Project Structure

```text
Agritech-app/
│
├── public/
│   └── favicon.ico
│
├── src/
│   └── index.html
│
├── .gitignore
└── README.md
```

The project intentionally keeps the application lightweight and does **not require a traditional backend server or npm build process** for the current implementation.

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/ayush-justdev/Agritech-app.git
cd Agritech-app
```

### 2. Run the Application

Open the following file directly in a modern web browser:

```text
src/index.html
```

No `npm install`, `ng serve`, or Angular CLI setup is required for the current version.

> 🌐 **Internet connection is required** because the application loads AngularJS and communicates with external APIs.

---

## 🔐 API Configuration & Security

The application uses external APIs for weather and market-price information.

Before publishing or deploying the project:

* Do **not** commit private API keys.
* Keep sensitive credentials outside publicly accessible source files.
* Use placeholders or environment-based configuration where possible.
* Rotate any API key that may have previously been exposed.

Example:

```text
YOUR_OPENWEATHER_API_KEY
YOUR_DATA_GOV_API_KEY
```

> ⚠️ Never upload real API credentials to a public GitHub repository.

---

## 🎯 Project Objective

The main objective of this project is to develop a **simple digital agricultural assistance platform** that combines multiple useful farming utilities into one centralized dashboard.

Instead of accessing separate tools for weather, crop planning, yield estimation, market information, and farm activities, users can access these features through a single interface.

---

## 🌾 Real-World Applications

The dashboard can be extended for:

* 👨‍🌾 Farmer assistance systems
* 🌱 Crop planning
* 🌦️ Weather-based agricultural decisions
* 💰 Agricultural market monitoring
* 🧪 Basic fertilizer guidance
* 📋 Farm activity management
* 🎓 Agricultural technology learning projects

---

## 📚 Learning Outcomes

This project demonstrates practical experience with:

* Frontend web development
* AngularJS application structure
* JavaScript-based application logic
* REST API integration
* JSON data handling
* Responsive UI development
* Rule-based recommendation systems
* Client-side calculations
* Dashboard design
* Git and GitHub project management

---

## 🔮 Future Enhancements

Possible improvements include:

* 📍 GPS-based location detection
* 🤖 AI-powered crop recommendations
* 🦠 AI-based crop disease detection
* 📊 Agricultural analytics and charts
* 🔔 Weather and farming alerts
* ☁️ Cloud-based farm data storage
* 👤 User accounts and personalized dashboards
* 📱 Progressive Web App support
* 🌐 Multi-language support for farmers

---

## 📌 Project Status

**Current Status:** 🟢 Core dashboard implemented

The primary agricultural utilities are implemented, with further improvements and optimization planned for future versions.

---

## 👨‍💻 Author

**Ayush**

Computer Engineering Student
Interested in Android Development, Web Development, C++, Java, and emerging technologies.

---

## 📄 License

This project is licensed under the **MIT License**.

---

⭐ If you find this project useful or interesting, consider giving the repository a star!
