
# 🌤️ WeatherNow – Real-Time Weather Application

A Python-based weather application that fetches real-time weather information for a given city using a Weather API.

This project demonstrates how to integrate external APIs into Python applications, securely manage API keys, and process JSON responses.

## 🚀 Features

- Fetch real-time weather information for any supported city.
- Display temperature, humidity, and weather conditions.
- Retrieve weather data using API requests.
- Handle API responses and errors.
- Use API key authentication to access weather data.

## 🛠️ Technologies Used

- Python
- Weather API
- Requests Library
- JSON
- API Key Authentication

## ⚙️ How It Works

1. The user enters a city name.
2. The application sends an HTTP request to the Weather API.
3. The API key is used to authenticate the request.
4. The API returns weather information in JSON format.
5. The application processes the response and displays the weather details.

## 📦 Installation

### 1. Clone the repository

```bash
git clone https://github.com/Kowsalya-V/WeatherNow.git
cd WeatherNow
```

### 2. Install dependencies

```bash
pip install requests
```

### 3. Configure your API key

Create a `.env` file in the project directory:

```env
WEATHER_API_KEY=your_api_key_here
```

Replace the placeholder with your actual API key.

### 4. Run the application

```bash
python main.py
```

## 🔐 API Key Security

- Keep your API key private.
- Store the key in a `.env` file.
- Add `.env` to `.gitignore` to prevent it from being uploaded to GitHub.
- Never share your actual API key in public repositories.

## 📚 Learning Outcomes

- Understanding API integration in Python.
- Fetching data using HTTP GET requests.
- Working with JSON responses.
- Using API keys for authentication.
- Handling API errors and exceptions.

