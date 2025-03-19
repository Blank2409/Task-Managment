# Task Management System

A full-stack task management application built with **Spring Boot** (backend) and **React** (frontend). The system includes microservices for user management, task tracking, and submission handling, all orchestrated via a **Gateway Service**.

---

## Features
- **User Authentication**: Sign up, log in, and manage user profiles.
- **Task Management**: Create, update, and track tasks.
- **Submission Handling**: Submit and review task submissions.
- **Microservices Architecture**: Built with Spring Boot microservices and a centralized Gateway.
- **Frontend**: Responsive React app hosted on Vercel.
- **Backend**: Spring Boot microservices deployed on Railway.

---

## Technologies Used
### Backend
- **Spring Boot**: Microservices framework.
- **Spring Cloud Gateway**: API Gateway for routing requests.
- **MySQL**: Database for each microservice.
- **Railway**: Deployment platform for backend services.

### Frontend
- **React**: Frontend library for building user interfaces.
- **Axios**: HTTP client for API requests.
- **Vercel**: Deployment platform for the React app.

---

## Architecture
Frontend (Vercel)
│
└─ Gateway Service (Railway)
│
├─ User Service (Railway + MySQL)
├─ Task Service (Railway + MySQL)
└─ Submission Service (Railway + MySQL)


---

## Getting Started
### Prerequisites
- Java 17
- Node.js 16+
- MySQL

### Backend Setup
1. Clone the repository:
   ```
   git clone https://github.com/your-username/task-management-system.git
   
---

## Getting Started
### Prerequisites
- Java 17
- Node.js 16+
- MySQL

### Backend Setup
1. Clone the repository:
   ```
   git clone https://github.com/your-username/task-management-system.git
---
 2.Navigate to each service directory (e.g., user-service, task-service) and build the project:
   ./mvnw clean package

### Frontend Setup

1.Navigate to the frontend directory:
cd frontend

2.Install dependencies:
npm install

3.Start the development server:
npm start


## ScreenShots
### Login
![image](https://github.com/user-attachments/assets/452f4dd8-236f-41d3-a6fb-ebbb8c3670fb)
![image](https://github.com/user-attachments/assets/0a60dc6a-9f13-42a1-bc39-19bc404e5cef)

### Home 
![image](https://github.com/user-attachments/assets/6e6e7c53-6b86-408e-bae2-c35a5bc0d3b3)

Create new Task
![image](https://github.com/user-attachments/assets/9033454e-61e9-45e1-b2f1-d67813423cc3)

Assigned User
![image](https://github.com/user-attachments/assets/2584189d-1975-43e8-836f-20508a8f0127)





