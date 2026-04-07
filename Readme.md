# 🚀 Real-Time Messaging Platform

A real-time messaging system built using **Spring Boot** and **WebSocket (STOMP)** to enable low-latency, bidirectional communication between multiple users.

---

## ✨ Features

* 🔄 Real-time bidirectional communication
* 👥 Multi-user chat support
* 📡 Message broadcasting using WebSockets
* ⚡ Low-latency event-driven architecture
* 🔌 Persistent connection handling

---

## 🛠 Tech Stack

* **Backend:** Java, Spring Boot
* **Protocol:** WebSocket (STOMP)
* **Build Tool:** Maven

---

## 🧠 System Design Overview

* Clients establish a persistent WebSocket connection with the server
* Messages are routed using the STOMP protocol
* Server handles concurrent users using asynchronous event-driven processing
* Reduces latency compared to traditional HTTP-based communication

---

## 📂 Project Structure

```
src/main/java       → Backend logic  
src/main/resources  → Configuration files  
pom.xml             → Dependencies  
```

---

## ▶️ How to Run

```bash
# Clone the repository
git clone https://github.com/ReetuPailla/real-time-messaging-platform.git

# Navigate into project
cd real-time-messaging-platform

# Run the application
./mvnw spring-boot:run
```

Then open your browser:
http://localhost:8080

---

## 👨‍💻 Author

Reetu Pailla

---

## 🔗 GitHub

https://github.com/ReetuPailla/real-time-messaging-platform

