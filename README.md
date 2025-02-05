# API_INTEGRATION
# **Enhanced Weather App**

This is a simple weather application that fetches weather data for a given city or the user's current location using the OpenWeatherMap API. The app displays current weather conditions, including temperature, humidity, wind speed, sunrise, and sunset times. Additionally, it maintains a history of searched cities.

## **Features**
- **City Search**: Enter the name of a city to get its weather information.
- **Current Location**: Use the current location of the user to get weather data.
- **Weather Display**: Displays temperature, weather description, humidity, wind speed, sunrise, and sunset times.
- **Search History**: Displays previously searched cities and allows users to view their past searches.

## **Tech Stack**
- HTML
- CSS
- JavaScript (Fetch API)
- OpenWeatherMap API

## **Setup Instructions**

### **1. Clone the Repository**
Clone this repository to your local machine using the following command:
```bash
git clone https://github.com/BhavanaRangarao19/Task1.git
```

### **2. Create an OpenWeatherMap API Key**
You will need an **API key** to make requests to OpenWeatherMap's API. Follow these steps to get your API key:
1. Go to the [OpenWeatherMap API](https://openweathermap.org/api) website.
2. Sign up for a free account or log in if you already have one.
3. After logging in, go to your [API keys](https://home.openweathermap.org/api_keys) page.
4. Copy your **API key**.

### **3. Add Your API Key to the Project**
In the `script` section of your HTML file, replace the `apiKey` value with your **API key**:
```javascript
const apiKey = 'your-api-key-here';
```

### **4. Open the Project**
Once you've updated the API key, open the `index.html` file in your browser to run the weather app.

### **5. Optional: Customization**
You can further customize the app by modifying the CSS styles and adding more features such as weather forecasts for the next few days.

## **How It Works**

### **1. Fetch Weather by City**
When the user enters a city name and clicks the "Get Weather" button, the app makes a request to OpenWeatherMap's current weather API and displays the weather data.

### **2. Fetch Weather by Current Location**
The user can click the "Use Current Location" button, which will prompt for geolocation access, and the app will fetch weather data based on the user's location.

### **3. Weather Data Display**
The app displays:
- City name
- Weather icon
- Temperature in both Celsius and Fahrenheit
- Weather description
- Humidity
- Wind speed
- Sunrise and sunset times

### **4. Search History**
The app keeps track of the cities the user has searched for and displays them in the "Search History" section. The history is saved in the browser's local storage, so the data persists between page reloads.

## **Troubleshooting**
- If you encounter issues with fetching data, ensure your **API key** is correct and not expired.
- If the location access is denied, ensure that your browser has permission to access location services.

## **Contributing**
Feel free to fork the repository and submit issues or pull requests to improve the app.


**OUTPUT**

![Initial](https://github.com/user-attachments/assets/57230196-3222-45b2-ad7a-becfa01048bf)
![GetWeather](https://github.com/user-attachments/assets/ce2ffd88-5a28-4eaa-8a28-a7392530e86b)
![CurentLocation](https://github.com/user-attachments/assets/31a39084-f5f2-4cce-b99a-685619935df3)
![CurrentLocation2](https://github.com/user-attachments/assets/c9c2f135-5659-4221-b032-9597ddcf2675)
![GetWeather2](https://github.com/user-attachments/assets/d439719e-b182-4f49-b8bb-aad6b9dbdabf)

