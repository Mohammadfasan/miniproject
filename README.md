# 🎓 University School Learning Management System

A comprehensive, modern Learning Management System (LMS) built with Next.js, TypeScript, Node.js, and MongoDB. Designed to streamline educational processes for universities and schools with real-time features and responsive design.

![Next.js](https://img.shields.io/badge/Next.js-14-Frontend-blue)
![Node.js](https://img.shields.io/badge/Node.js-Backend-green)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-brightgreen)
![TypeScript](https://img.shields.io/badge/TypeScript-Full--Stack-3178C6)
![Status](https://img.shields.io/badge/Status-Development-yellow)


## ✨ Features

### 🏫 Institution Management
- Multi-school/university support
- Department and program management
- Academic calendar and scheduling
- Staff and faculty management

### 👨‍🏫 Faculty Features
- Course creation and management
- Assignment distribution and grading
- Attendance tracking
- Grade book management
- Announcement system
- Student progress monitoring

### 👨‍🎓 Student Features
- Course enrollment
- Assignment submission
- Grade viewing
- Attendance tracking
- Resource access
- Progress dashboard
- Discussion forums

### 📚 Course Management
- Curriculum design
- Resource sharing (PDFs, Videos, Links)
- Quiz and exam creation
- Discussion forums
- Real-time notifications
- Progress tracking

### 📊 Analytics & Reporting
- Student performance analytics
- Attendance reports
- Course statistics
- Institutional insights
- Export capabilities

## 👥 User Roles

### 🎯 Administrator
- Full system control
- User management (students, teachers, staff)
- Course and program setup
- System configuration
- Analytics and reporting

### 👨‍🏫 Teacher/Faculty
- Course management
- Student grading
- Attendance recording
- Resource sharing
- Communication with students

### 👨‍🎓 Student
- Course participation
- Assignment submission
- Progress tracking
- Resource access
- Peer interaction

### 👨‍💼 Parent (Future)
- Student progress monitoring
- Attendance tracking
- Communication with teachers

## 🛠 Tech Stack

### Frontend
* **Framework:** Next.js 14 (App Router)
* **Language:** TypeScript
* **Styling:** Tailwind CSS + Shadcn/UI
* **State Management:** Zustand/Redux Toolkit
* **Forms:** React Hook Form with Zod validation
* **Charts:** Recharts/Chart.js
* **Real-time:** Socket.io Client

### Backend
* **Runtime:** Node.js
* **Framework:** Express.js
* **Database:** MongoDB with Mongoose
* **Authentication:** JWT + Bcrypt
* **File Upload:** Multer + Cloud Storage
* **Real-time:** Socket.io
* **Email:** Nodemailer

### DevOps & Tools
* **Containerization:** Docker
* **Deployment:** Vercel (Frontend), Railway/Render (Backend)
* **Database:** MongoDB Atlas
* **CI/CD:** GitHub Actions
* **Monitoring:** Sentry

## 📸 Screenshots

*(Add your application screenshots here)*

| Dashboard | Course Management | Gradebook |
|:---:|:---:|:---:|
| <img src="screenshots/dashboard.png" width="250"> | <img src="screenshots/courses.png" width="250"> | <img src="screenshots/gradebook.png" width="250"> |

| Assignment | Analytics | Profile |
|:---:|:---:|:---:|
| <img src="screenshots/assignment.png" width="250"> | <img src="screenshots/analytics.png" width="250"> | <img src="screenshots/profile.png" width="250"> |

## 💻 Installation

### Prerequisites
- Node.js (v18 or above)
- MongoDB (Local or Atlas)
- Git

### Frontend Setup

1. **Clone Frontend Repository**
   ```bash
   git clone https://github.com/your-username/university-lms-frontend.git
   cd university-lms-frontend
   ```

2. **Install Dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Start Development Server**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

### Backend Setup

1. **Clone Backend Repository**
   ```bash
   git clone https://github.com/your-username/university-lms-backend.git
   cd university-lms-backend
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Setup Environment**
   ```bash
   cp .env.example .env
   ```

4. **Start Development Server**
   ```bash
   npm run dev
   # or
   npm start
   ```

