# 🌍 Trip Planner

Trip Planner is a simple web application built with **HTML, CSS, and JavaScript** that helps users explore destinations, view photos, and check live weather conditions.  
It integrates with the **Unsplash API** for photos and the **OpenWeatherMap API** for weather updates.  

---

## 🚀 Features
- 🔎 Search for any city worldwide.  
- 🌤️ Get live weather information (temperature, humidity, condition, wind).  
- 🖼️ View high-quality images of the destination from Unsplash.  
- 🎨 Clean and responsive interface.  

---

## 📂 Project Structure
Travel Explorer Website
|--index.html# Main HTML file
|--style.css # Stylesheet
|--script.js # JavaScript(API calls + DOM updates)


---

## 🛠️ Setup Instructions

### 1. Clone or Download
Download the project and open it in your code editor (VS Code recommended).

### 2. Get API Keys
- **Unsplash API Key**  
  1. Go to [Unsplash Developers](https://unsplash.com/developers).  
  2. Create a new application.  
  3. Copy the **Access Key**.  

- **OpenWeatherMap API Key**  
  1. Go to [OpenWeatherMap](https://openweathermap.org/api).  
  2. Sign up and log in.  
  3. Find your API key under **Profile > My API keys**.  

### 3. Add API Keys
Open `script.js` and replace:
```js
const WEATHER_API_KEY = "your_openweather_api_key";
const UNSPLASH_ACCESS_KEY = "your_unsplash_api_key";

###4.Run the project
   1. Open index.html in your browser.
   2.(Recommended) Run with Live Server...VS Code.
   3.Start a simple local server:
   python -m http.server 8000
   then open http://localhost:8000