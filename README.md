# 🏋️‍♂️ FitnessAI

FitnessAI is a scalable, microservices-based fitness platform that combines backend services, AI intelligence, and a modern frontend to deliver personalized fitness tracking and recommendations.

The project is built using Spring Boot microservices, Spring Cloud for service orchestration, and a JavaScript frontend.

---

## 🚀 Architecture Overview

The project follows a distributed microservices architecture:

FitnessAI/
│
├── fitness-frontend/     # Frontend UI (React / JavaScript)
├── gateway/              # API Gateway
├── eureka/               # Service Discovery (Eureka Server)
├── configserver/         # Centralized Configuration Server
├── userservice/         # User management and authentication
├── activityservice/     # Workout & activity tracking
├── aiservice/           # AI-powered fitness recommendations

---

## ✨ Features

- 👤 User registration and profile management  
- 🏃 Activity and workout tracking  
- 🤖 AI-powered fitness recommendations  
- 🌐 API Gateway for unified routing  
- 🔍 Service discovery using Eureka  
- ⚙ Centralized configuration with Config Server  
- 💻 Modern frontend UI  

---

## 🛠 Tech Stack

Backend:
- Java
- Spring Boot
- Spring Cloud (Eureka, Config Server, Gateway)
- REST APIs

Frontend:
- JavaScript (React or modern JS framework)
- HTML, CSS

DevOps:
- Maven
- Docker (optional)
- GitHub

---

## 🧪 Getting Started

Prerequisites:
- Java 11+
- Node.js & npm
- Maven
- Git

---

## 📥 Clone the Repository

git clone https://github.com/PrakharS-18/FitnessAI.git  
cd FitnessAI  

---

## ▶ Run Backend Services

Start services in the following order:

1. Eureka Server  
cd eureka  
mvn spring-boot:run  

2. Config Server  
cd configserver  
mvn spring-boot:run  

3. API Gateway  
cd gateway  
mvn spring-boot:run  

4. Other Services  

cd userservice  
mvn spring-boot:run  

cd activityservice  
mvn spring-boot:run  

cd aiservice  
mvn spring-boot:run  

---

## 🌐 Run Frontend

cd fitness-frontend  
npm install  
npm start  

Open:  
http://localhost:3000  

---

## 📦 Optional: Docker Deployment

docker build -t fitnessai-userservice userservice/  
docker build -t fitnessai-activityservice activityservice/  

---

## 🤝 Contributing

1. Fork the repository  
2. Create a feature branch  
3. Commit your changes  
4. Submit a Pull Request  

---

## 📄 License

Add your license here (MIT / Apache 2.0 / etc.)

---

## 📬 Author

Developed by Prakhar S

⭐ If you like this project, don't forget to star the repository!
