# 🚀 HireTrack — Full-Stack Job Application Tracker

> A production-inspired full-stack application that helps job seekers organize, monitor, and analyze their job application process with authentication, analytics, automated follow-up reminders, and Dockerized deployment.

<p align="center">
  <img src="https://img.shields.io/badge/React-19-blue?logo=react">
  <img src="https://img.shields.io/badge/Node.js-Express-green?logo=node.js">
  <img src="https://img.shields.io/badge/PostgreSQL-Database-blue?logo=postgresql">
  <img src="https://img.shields.io/badge/Docker-Containerized-2496ED?logo=docker">
  <img src="https://img.shields.io/badge/JWT-Authentication-orange">
  <img src="https://img.shields.io/badge/License-MIT-success">
</p>

---

# 📌 Overview

Keeping track of dozens of job applications across multiple companies quickly becomes overwhelming. HireTrack solves this problem by providing a centralized dashboard where users can:

- Track job applications
- Monitor application progress
- Receive follow-up reminders
- Analyze application statistics
- Export application data
- Securely manage their account

The project demonstrates real-world full-stack development practices including authentication, REST APIs, scheduled background jobs, containerization, and responsive frontend development.

---

# ✨ Features

## 🔐 Authentication

- User Registration
- Secure Login
- JWT Authentication
- Refresh Token Mechanism
- Protected Routes
- Persistent Sessions
- Secure Password Hashing using bcrypt

---

## 📋 Application Management

Manage every job application from one dashboard.

Users can:

- Add new applications
- Edit existing applications
- Delete applications
- Search by company or role
- Filter by status
- Track interview progress
- Store notes
- Save job URLs
- Record salary ranges
- Track locations
- Export applications as CSV

---

## 📊 Analytics Dashboard

Interactive dashboard providing insights such as:

- Total Applications
- Status Distribution
- Weekly Activity
- Upcoming Follow-ups
- Hiring Funnel Visualization

This allows users to monitor their job search performance over time.

---

## 📧 Automated Email Reminders

HireTrack includes a scheduled reminder system that automatically checks for upcoming follow-ups and sends email notifications.

Built using:

- node-cron
- Nodemailer

This feature simulates real-world background task scheduling found in production applications.

---

## 🐳 Docker Support

Entire application can be launched with a single command using Docker Compose.

Containers include:

- Frontend
- Backend
- PostgreSQL Database

This makes local development and deployment simple and consistent.

---

# 🏗️ Tech Stack

## Frontend

- React
- Vite
- React Router
- Axios
- Context API

---

## Backend

- Node.js
- Express.js
- JWT
- bcrypt
- node-cron
- Nodemailer

---

## Database

- PostgreSQL

---

## DevOps

- Docker
- Docker Compose
- Nginx

---

# 📂 Project Structure

```
HireTrack
│
├── frontend/
│   ├── src/
│   ├── components/
│   ├── pages/
│   ├── context/
│   └── api/
│
├── backend/
│   ├── controllers/
│   ├── routes/
│   ├── middleware/
│   ├── config/
│   └── database/
│
├── docker-compose.yml
└── README.md
```

---

# 🔄 Application Flow

```
User
   │
   ▼
React Frontend
   │
Axios API Calls
   │
Express Server
   │
Authentication Middleware
   │
Controllers
   │
PostgreSQL Database
   │
Response
   │
Dashboard/UI Update
```

---

# 🔐 Authentication Flow

```
Register/Login

        │

        ▼

Password Hashing

        │

        ▼

JWT Access Token

        │

        ▼

Protected API Access

        │

        ▼

Automatic Token Refresh
```

---

# 📊 Dashboard Features

✔ Summary Cards

✔ Status Breakdown

✔ Weekly Activity

✔ Upcoming Follow-Ups

✔ Interactive Charts

---

# 📧 Reminder System

```
Cron Scheduler

      │

      ▼

Check Follow-up Dates

      │

      ▼

Send Reminder Email

      │

      ▼

User Notification
```

---

# 🚀 Getting Started

## Clone Repository

```bash
git clone https://github.com/yourusername/HireTrack.git

cd HireTrack
```

---

## Run with Docker

```bash
docker compose up --build
```

---

## Backend

```bash
cd backend

npm install

npm run dev
```

---

## Frontend

```bash
cd frontend

npm install

npm run dev
```

---

# ⚙ Environment Variables

Backend `.env`

```env
PORT=5000

DATABASE_URL=

JWT_SECRET=

JWT_REFRESH_SECRET=

EMAIL_USER=

EMAIL_PASSWORD=
```

---

# 📈 Highlights

- Production-style project architecture
- RESTful API Design
- Secure JWT Authentication
- Refresh Token Strategy
- Background Cron Jobs
- Dockerized Development
- PostgreSQL Integration
- CSV Export Functionality
- Analytics Dashboard
- Responsive UI
- Clean Folder Structure
- Modular Backend
- Context-based State Management

---

# 🧠 Software Engineering Concepts Demonstrated

- Authentication & Authorization
- REST API Design
- Middleware Architecture
- MVC Pattern
- Database Design
- Scheduled Background Jobs
- State Management
- Protected Routing
- Containerization
- Error Handling
- Modular Code Organization
- Responsive Frontend Development

---

# 📸 Screenshots

> Add screenshots of:

- Login Page
- Dashboard
- Applications Page
- Analytics Charts
- Reminder Emails

---

# 🔮 Future Improvements

- OAuth Login (Google/GitHub)
- Resume Upload
- AI Resume Matching
- Interview Preparation Assistant
- Kanban Board
- Calendar Integration
- Push Notifications
- Mobile Responsive Enhancements
- Advanced Analytics
- Dark Mode

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository

2. Create your feature branch

3. Commit your changes

4. Push to your branch

5. Open a Pull Request

---

# ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

It helps others discover the project and motivates further improvements.
