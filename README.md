# Weather App (Vue.js)

A sleek, real-time weather application built with Vue 3 and Vite, styled with Tailwind CSS. This app allows users to search for cities globally and view current weather conditions along with a 3-day forecast.

**Live Demo:** [https://weather-app-vue-js-git-main-kelvinmutukus-projects.vercel.app](https://weather-app-vue-js-git-main-kelvinmutukus-projects.vercel.app)

## Features

* **Global Search:** Find weather data for any city using the WeatherAPI search autocomplete.
* **Dynamic Backgrounds:** The interface changes themes based on whether it is day or night in the selected location.
* **Detailed Forecast:** View temperature highs and lows for the next three days.
* **Weather Metrics:** Tracks wind speed, humidity, precipitation, UV index, and "feels like" temperatures.

## Tech Stack

* **Framework:** [Vue.js 3](https://vuejs.org/) (Composition API)
* **Build Tool:** [Vite](https://vitejs.dev/)
* **Styling:** [Tailwind CSS](https://tailwindcss.com/)
* **Icons:** [Font Awesome](https://fontawesome.com/)
* **API:** [WeatherAPI.com](https://www.weatherapi.com/)

## Local Setup

1. **Clone the repository:**
```sh
git clone https://github.com/kelvinmutuku/weather_app_vue.js.git
cd weather_app_vue.js

```


2. **Install dependencies:**
```sh
npm install

```


3. **Configure Environment Variables:**
Create a `.env` file in the root directory and add your WeatherAPI key:
```env
VITE_WEATHER_API_KEY=your_api_key_here

```


4. **Run the development server:**
```sh
npm run dev

```



## Deployment on Vercel

To host this yourself on Vercel:

1. Push your code to GitHub (ensure `.env` is in your `.gitignore`).
2. Import the project into Vercel.
3. In the **Environment Variables** settings, add `VITE_WEATHER_API_KEY` with your actual API key.
4. Deploy.