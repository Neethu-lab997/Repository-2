
# A sample API document requirement

## Introduction
Door contacts are essential for home and business security systems, as they provide real-time monitoring of entry points, ensuring that any unauthorized access is immediately detected. It communicates with the Paradox M systems using 2-way wireless communication, featuring the latest Gaussian Frequency Shift Keying (GFSK) technology with frequency and encryption hopping. This ensures superior wireless range, enhanced encryption, supervision, and reliability. It is typically used to monitor the opening of doors and windows. DCT12M can support a magnet-activated wireless zone and an additional cabled zone input simultaneously. The additional wired zone can transmit the device’s status wirelessly. The wired input zone supports configurations with no EOL resistor, one EOL resistor, or two EOL resistors.

## Quick Installation
To install DCT12M:
1.	Unscrew the device from the bottom, then open the sensor.
2.	Fix the backplate and the magnet, ensuring proper alignment.
3.	Connect the external wired zone with or without an EOL resistor.
4.	Remove the battery tab and close the sensor.
5.	Pair DCT12M with the console (Using the BlueEye application):
•	Go to: Hardware > Tap Add Devices > Wireless Devices Auto learn/Scan QR code or add devices manually (by entering serial number).
NOTE: You can instantly pair DCT12M by pressing the Learn button, or by opening the tamper or a zone.
6.	Configure DCT12M (Using the BlueEye application):
•	Go to: Hardware > Tap DCT12M from the device list > Enter the necessary details > Save.
Built-in status indications of DCT12M:
•	Red – DCT12M not connected to the wireless console
•	Green – Magnet attached; zone closed
•	Yellow – Magnet detached; zone open
•	Red/Green – Tamper alarm activation


---

## 📌 Physical Mounting

NOTE: Installing the door contact on large metal surfaces may interfere with wireless signals and reduce performance.
To mount the DCT12M door contact:
1.	Unscrew the device from the bottom. 
2.	Press the Opening Tab at the bottom of the device with a flat-head screwdriver and lift the front cover to remove it.
3.	Fix the backplate on the wall with two screws. 
NOTE: As per the EN security standards, one screw must be secured in the tamper hole. The use of double-sided tape does not trigger a wall tamper alarm.
4.	Connect the external wired zone with or without an EOL resistor

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
