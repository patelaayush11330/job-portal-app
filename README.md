💼 Job Portal App

A full-stack web application built with **Spring Boot (Java)** for the backend and **React.js** for the frontend. 
This project allows students to **register**, **log in**, manage their **profile**, and **upload resumes**, simulating a mini job portal platform.

🔧 Tech Stack

| Layer     | Technology            |
|-----------|------------------------|
| Backend   | Spring Boot, Spring Data JPA, Spring Security |
| Frontend  | React.js, React Router DOM |
| Database  | H2 (in-memory)         |
| Tools     | Maven, Postman         |
| Language  | Java, JavaScript       |


🚀 Features

✅ Student Authentication
- Registration with name, email, and password
- Login using email and password
- Passwords are securely hashed using `BCryptPasswordEncoder`

✅ Profile Management
- Display student details post login
- View dashboard

✅ Resume Upload (Upcoming)
- Feature placeholder included

🗂️ Project Structure
job-portal-app/
├── backend/ # Spring Boot Backend
│ ├── controller/ # REST API endpoints
│ ├── model/ # JPA entities
│ ├── repository/ # Data access layer
│ ├── service/ # Business logic
│ └── resources/ # application.properties
├── frontend/ # React Frontend
│ ├── pages/ # Login, Register, Dashboard
│ └── App.js # Main routing
├── postman_collection.json # Sample API collection for testing


⚙️ Getting Started

1. Clone the Repository:
git clone  https://github.com/patelaayush11330/job-portal-app.git
cd job-portal-app

2. Run Backend (Spring Boot)

cd backend
./mvnw spring-boot:run     # or mvn spring-boot:run
📍 Backend runs on: http://localhost:8080

You can access the H2 Console at: http://localhost:8080/h2-console


