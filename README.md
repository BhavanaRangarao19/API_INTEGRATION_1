# API_INTEGRATION_1

**

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

1)Initial Page
https://github.com/user-attachments/assets/99a32af8-0bec-44e1-8209-9363bdc311df

2)Weather in a given city(Mumbai)
https://github.com/user-attachments/assets/553df900-900e-42c1-b280-0855364babbb

3)Allow the location access
https://github.com/user-attachments/assets/f6842db8-2b66-4b93-889c-267b30b71058

4)Weather in current location
https://github.com/user-attachments/assets/ae22d833-c8ee-4b56-96ad-bca950c9b040

5)Weather in a given city(Tokyo)
https://github.com/user-attachments/assets/f471bef3-4a07-4b0c-be2d-be23b399dc6b
