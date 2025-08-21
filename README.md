# 🌦️ Weather App

A simple weather web application built with **HTML, CSS, and JavaScript** that allows users to check real-time weather information for cities worldwide. The app integrates with the [OpenWeather API](https://openweathermap.org/api) and provides an intuitive search experience with **autocomplete suggestions** for countries and cities.

---

## ✨ Features

* 🔍 **Search by city**: Enter the name of any city to get current weather.
* 📡 **Live weather data**: Fetches temperature, humidity, wind speed, and conditions using OpenWeather API.
* 🌍 **Autocomplete suggestions**: Includes a curated list of **countries and major global cities** for quick selection.
* 🖼️ **Dynamic weather icons**: Icons change based on real-time weather (clouds, clear, rain, drizzle, mist).
* 📱 **Responsive design**: Works across desktop and mobile devices.

---

## 🚀 Demo

![Weather App Screenshot](<img width="752" height="717" alt="image" src="https://github.com/user-attachments/assets/40002c10-91e5-428c-874f-bff59346ed70" />
)

---

## 🛠️ Tech Stack

* **Frontend**: HTML5, CSS3, JavaScript
* **API**: [OpenWeather API](https://openweathermap.org/)
* **Icons**: Custom weather icons stored in `./Asset/`

---

## ⚙️ Installation & Setup

1. Clone this repository:

   ```bash
   git clone https://github.com/Kamrul-Hasan-Rimon/Weather-App.git
   ```
2. Navigate into the project directory:

   ```bash
   cd weather-app
   ```
3. Open `index.html` in your browser.

---

## 🔑 API Key Setup

This app requires an API key from **OpenWeather**:

1. Sign up at [OpenWeather](https://home.openweathermap.org/users/sign_up).
2. Copy your API key.
3. Replace the placeholder in `index.html`:

```javascript
const apikey = "eac6f1f8c57238650553cc7293cee1e2";
```

---

## 📂 Project Structure

```
weather-app/
├─ index.html
├─ style.css
├─ script.js     
├─ Asset/
│  ├─ clear.png
│  ├─ clouds.png
│  ├─ drizzle.png
│  ├─ humidity.png
│  ├─ mist.png
│  ├─ rain.png
│  └─ wind.png
└─ README.md

```

---

## 📸 Preview

### Search & Suggestions

* Start typing a city or country → Autocomplete list appears.
* Click a suggestion → Weather details load instantly.

### Weather Details

* City name
* Temperature (°C)
* Humidity (%)
* Wind speed (km/h)
* Weather icon (based on conditions)

---

## 🚧 Future Improvements

* 🌐 Add support for multi-language weather data.
* 📍 Fetch weather by **user’s current location (Geolocation API)**.
* ⏳ Show **5-day weather forecast**.
* 🎨 Dark mode toggle.

---

## 📜 License

This project is licensed under the **MIT License** – feel free to use, modify, and distribute it.

---

Do you want me to also **add Markdown badges (like “Made with JavaScript”, “OpenWeather API”, etc.)** to make your README look even more professional?
