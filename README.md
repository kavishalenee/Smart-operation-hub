# Smart Operation Hub 🚀

A comprehensive full-stack management system designed to streamline operations, built with modern enterprise-grade technologies.

## 🛠️ Tech Stack
*   **Frontend:** React.js (Responsive UI)
*   **Backend:** Spring Boot (Java RESTful APIs)
*   **Database:** MongoDB (NoSQL for flexible data storage)
*   **Data Visualization:** MongoDB Compass
*   **Containerization:** Docker & Docker Compose

## ✨ Key Features
*   **Real-time Operations Tracking:** Efficiently manage and monitor tasks.
*   **Robust Backend:** High-performance APIs built with Spring Boot.
*   **Scalable Database:** NoSQL architecture using MongoDB.
*   **Easy Deployment:** Fully containerized setup using Docker for consistent environments.

## 🚀 Getting Started

### Prerequisites
- Java Development Kit (JDK 17+)
- Node.js (v16+)
- MongoDB (Local or Atlas)
- Docker Desktop (Optional but recommended)

### Installation & Setup

#### 1. Backend (Spring Boot)
1. Navigate to the backend directory: `cd backend`
2. Run the application: `./mvnw spring-boot:run`
*The server will start on port 8080.*

#### 2. Frontend (React)
1. Navigate to the frontend directory: `cd frontend`
2. Install dependencies: `npm install`
3. Start the dev server: `npm run dev` (or `npm start`)
*The application will be available at http://localhost:5173 or 3000.*

#### 3. Docker (Easiest Method)
To run the entire stack (Frontend, Backend, and MongoDB) simultaneously:
```bash
docker-compose up --build
