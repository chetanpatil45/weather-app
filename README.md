# 🌤️ Weather Application

A modern Weather Forecast Web Application built using **Spring Boot** that allows users to search any city and view current weather details along with a 5-day forecast.

---

## 📌 Features

* 🔍 Search weather by city name
* 🌡️ View current temperature
* 💧 Humidity details
* 🌬️ Wind speed information
* 🔵 Atmospheric pressure
* 👀 Visibility range
* 🌅 Sunrise & Sunset timing
* 📅 5-Day weather forecast

---

## 🛠️ Tech Stack

| Layer             | Technology                                            |
| ----------------- | ----------------------------------------------------- |
| **Language**      | Java                                                  |
| **Framework**     | Spring Boot                                           |
| **Frontend**      | Thymeleaf, HTML5, CSS3, JavaScript                    |
| **API**           | OpenWeatherMap API                                    |
| **Server**        | Apache Tomcat 10.1                                    |
| **Build Tool**    | Maven                                                 |
| **Concepts Used** | RestTemplate, IoC, Dependency Injection, RESTful APIs |

---

## 🏗️ Architecture

* **Controller Layer** → Handles HTTP requests
* **Service Layer** → Calls OpenWeather API using `RestTemplate`
* **Frontend Layer** → Displays weather data using Thymeleaf & JavaScript
* **External API** → OpenWeatherMap API

---

## 🚀 How It Works

1. User enters a city name.
2. Application sends request to Spring Boot controller.
3. Service layer calls OpenWeather API.
4. API response is parsed and sent to frontend.
5. UI displays current weather + 5-day forecast.

---



## 📂 Project Structure

```
├── src/main/java
|    ├── controller
|    |    ├── HomeController.java  //controller with @Controller for load view's
|    |    └── WeatherController.java  // controller with @RestController for managing RESTful API's, Sending JSON responses.
|    ├── service/
|    |    └── WeatherService.java   // service class to send request and getting response from API endpoints using RestTemplate.
|    └── WeatherAppApplication.java  //main class
├── src/main/resources
     ├── static/
     |   └── img.png // screenshot
     ├── templates/
     |   ├── index.html
     |   └── info.html
     └── application.properties   //configuration file, all configurations mentioned here. like ApiKey, API endpoint etc.
```

---

## 📸 Screenshots
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/67acd87e-8e75-4ae3-ba78-2b4d1a18baf7" />


---

## 👨‍💻 Author
**Chetan** </br>
Java | Spring Boot Developer
