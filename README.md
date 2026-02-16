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
* 🎨 Modern glass UI design

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

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/weather-application.git
cd weather-application
```

### 2️⃣ Configure API Key

Add your OpenWeather API key inside:

```properties
application.properties
```

```properties
weather.api.key=YOUR_API_KEY
```

### 3️⃣ Build the Project

```bash
mvn clean install
```

### 4️⃣ Run the Application

```bash
mvn spring-boot:run
```

OR run from your IDE.

---

## 🌐 Access the Application

Open your browser:

```
http://localhost:8081
```

---

## 📂 Project Structure

```
src/
 ├── controller/
 ├── service/
 ├── templates/
 ├── static/
 └── application.properties
```

---

## 📸 Screenshots

*(Add your UI screenshots here)*

---

## 📈 Future Improvements

* Add hourly forecast
* Add location-based weather (GPS)
* Dark/Light theme toggle
* Add weather animations
* Deploy to cloud (AWS / Render / Railway)

---

## 👨‍💻 Author

**Chetan**
Java & Spring Boot Developer
