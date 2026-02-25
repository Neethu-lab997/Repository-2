# 🌤️ Montreal Weather App (branch of Rep 1.)

A simple web application that displays the current weather in Montreal using the OpenWeatherMap API.

This project demonstrates basic API integration, JavaScript fetch requests, and frontend display of real-time data.

---

## 📌 Features

* Retrieves live weather data from OpenWeatherMap
* Displays temperature, weather condition, and location
* Uses metric units (°C)
* Simple and clean user interface
* Runs entirely in the browser

---

## 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript (ES6)
* OpenWeatherMap REST API

---

## 🚀 How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/your-username/montreal-weather-app.git
```

2. Open the project folder.

3. Open `index.html` in your browser
   OR use Live Server in VS Code.

---

## 🔑 API Setup

This project requires an OpenWeatherMap API key.

1. Sign up at:
   https://openweathermap.org/

2. Generate an API key from your account dashboard.

3. Open `app.js` and replace:

```javascript
const API_KEY = "PASTE_YOUR_KEY_HERE";
```

with your actual API key.

---

## 📡 API Endpoint Used

```http
GET https://api.openweathermap.org/data/2.5/weather
```

### Query Parameters

| Parameter | Description       | Example     |
| --------- | ----------------- | ----------- |
| q         | City name         | Montreal,CA |
| units     | Measurement units | metric      |
| appid     | API key           | YOUR_KEY    |

---

## 📦 Example Request

```bash
curl "https://api.openweathermap.org/data/2.5/weather?q=Montreal,CA&units=metric&appid=YOUR_API_KEY"
```

---

## 📄 Example Response (Partial)

```json
{
  "name": "Montreal",
  "main": {
    "temp": 3.5,
    "humidity": 81
  },
  "weather": [
    {
      "description": "light snow"
    }
  ]
}
```

---

## 📁 Project Structure

```
montreal-weather-app/
│
├── index.html
├── app.js
├── style.css
└── README.md
```

---

## 🧪 Testing

You can test the API using tools such as:

* Postman
* curl
* Browser console

---

## 👩‍💻 Author

**Neethu Sunny**
Senior Technical Writer
Montreal, Canada

---

## 📜 License

This project is for educational and portfolio purposes only.

---

## ⭐ Acknowledgements

* OpenWeatherMap API
* VS Code Live Server
* GitHub
