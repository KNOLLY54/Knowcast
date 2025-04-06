# KnowCast - Weather App

KnowCast is a responsive weather application that provides real-time weather updates, 5-day forecasts, and additional features like saving locations, viewing search history, and toggling between light and dark themes. The app is built using HTML, CSS (TailwindCSS), and JavaScript.

---

## Features

### 1. **Real-Time Weather Updates**
   - Search for any city to get the current weather conditions.
   - Displays temperature, weather description, humidity, wind speed, and pressure.

### 2. **5-Day Weather Forecast**
   - Provides a 5-day forecast with daily weather summaries.

### 3. **Use Current Location**
   - Automatically fetches weather data for your current location using the Geolocation API.

### 4. **Search History**
   - Saves your recent searches and displays them in the history page.
   - Clicking on a history item fetches the weather for that location.

### 5. **Saved Locations**
   - Save frequently accessed locations for quick reference.
   - Manage saved locations from the "Locations" page.

### 6. **Dark Mode**
   - Toggle between light and dark themes.
   - Dark mode preference is saved and applied across all pages.

### 7. **Responsive Design**
   - Fully responsive for mobile, tablet, and desktop devices.

### 8. **Settings**
   - Change temperature units between Celsius and Fahrenheit.
   - Reset all saved data (search history, saved locations, and preferences).

---

## Pages

### 1. **Home Page (`index.html`)**
   - **Search Bar**: Enter a city name to fetch weather data.
   - **Use Current Location**: Fetch weather data for your current location.
   - **Weather Display**: Shows current weather and a 5-day forecast.
   - **Save Location**: Save the current city to the "Locations" page.
   - **Dark Mode Toggle**: Switch between light and dark themes.
   - **Refresh Button**: Reset the page to its original state.

### 2. **Search History Page (`history.html`)**
   - Displays a list of recently searched cities.
   - Clicking on a city fetches its weather data on the home page.
   - Includes a "Clear History" button to delete all search history.

### 3. **Saved Locations Page (`location.html`)**
   - Displays a list of saved locations.
   - Add your current location to the saved list.
   - Remove saved locations using the delete button.

### 4. **Settings Page (`settings.html`)**
   - Toggle between Celsius and Fahrenheit for temperature units.
   - Enable or disable dark mode.
   - Reset all saved data (search history, saved locations, and preferences).

---

## Installation

### Prerequisites
- A modern web browser (e.g., Chrome, Firefox, Edge).
- Internet connection (for fetching weather data).

### Steps
1. Clone the repository or download the project files.
   ```bash
   git clone https://github.com/your-repo/knowcast.git
