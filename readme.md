# FeedbackHub  

A fullstack web application for creating anonymous feedback rooms. Built with **NestJS**, **Drizzle ORM**, **MySQL**, and **Docker** on the backend, and **React**, **TypeScript**, and **TailwindCSS** on the frontend.  

The platform allows administrators to create and manage rooms where participants can submit anonymous feedback, ensuring privacy while fostering open communication.  

## ✨ Features  

- **Authentication & Authorization**  
  - JWT-based authentication  
  - Role-based access control with NestJS Guards  

- **Room Management**  
  - CRUD operations for feedback rooms  
  - Admin panel for managing rooms and participants  

- **Anonymous Feedback**  
  - Submit feedback without exposing identity  
  - Secure data flow between frontend and backend  

- **Documentation**  
  - Full API documentation with Swagger  

- **Deployment Ready**  
  - Dockerized environment (backend + database)  
  - Configurable via `.env` files  

## 🧱 Tech Stack  

### Backend  
- [NestJS](https://nestjs.com/) – Modular Node.js framework  
- [Drizzle ORM](https://orm.drizzle.team/) – Type-safe database ORM  
- [MySQL](https://www.mysql.com/) – Relational database  
- [Docker](https://www.docker.com/) – Containerized development environment  
- JWT for authentication  

### Frontend  
- [React](https://react.dev/) + [Vite](https://vitejs.dev/) – Modern frontend stack  
- [TypeScript](https://www.typescriptlang.org/) – Strongly typed development  
- [TailwindCSS](https://tailwindcss.com/) – Utility-first styling  

## 🚀 Getting Started  

### Prerequisites  
- Node.js (>= 18)  
- Docker & Docker Compose  
- MySQL client (optional, for DB inspection)  

### Backend Setup  

```bash
# Go to backend folder
cd backend

# Install dependencies
npm install

# Run Docker containers
docker-compose up -d

# Run migrations
npm run migration:run

# Start the backend
npm run start:dev
```

### Frontend Setup  

```bash
# Go to frontend folder
cd frontend

# Install dependencies
npm install

# Start the development server
npm run dev
```

## 📖 API Documentation  

Once the backend is running, access Swagger at:  

http://localhost:3000/api


## 🛠️ Future Improvements  

- Add token expiration refresh  
- Enhance UI with animations (Framer Motion)  
- Deploy to production (Vercel + Railway/DigitalOcean)  
- Add user analytics for admins  
