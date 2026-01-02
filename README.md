# Employee Feedback Dashboard

A full-stack web application designed to streamline and digitize employee feedback collection, replacing unorganized manual processes with a secure and scalable system.

---

## 📌 Project Overview

The Employee Feedback Dashboard allows employees to submit feedback easily while enabling administrators to manage, review, and control feedback securely.  
The project focuses on clean UI, modular backend design, and secure authentication.

---

## 🚀 Features

### 👨‍💼 Employee
- Submit feedback through a user-friendly interface
- View submitted feedback
- Secure authentication

### 🛠️ Admin
- View and manage employee feedback
- Delete or review feedback entries
- Role-based access control

### ⚙️ System
- Full CRUD operations
- RESTful APIs
- JWT-based authentication
- Responsive design

---

## 🧑‍💻 Tech Stack

### Frontend
- React.js  
- JavaScript (ES6+)  
- HTML5  
- CSS3 / Tailwind CSS  

### Backend
- Node.js  
- Express.js  

### Database
- MongoDB  
- Mongoose (ODM)  

### Authentication
- JSON Web Tokens (JWT)

### Tools
- Git  
- GitHub  
- VS Code  
- dotenv  

---

## 🏗️ Project Structure

```bash
employee-feedback/
│
├── config/
│   └── mongooseConfig.js
│
├── src/
│   ├── features/
│   ├── middlewares/
│   ├── views/
│
├── public/
│   ├── assets/
│   └── css/
│
├── .env
├── dotenv.js
├── index.js
├── package.json
└── README.md

---

##🔐 Authentication & Security

JWT-based authentication

Protected API routes using middleware

Role-based access control (Admin & Employee)

Environment variables secured using .env

---

##⚙️ Installation & Setup
Prerequisites

Node.js

MongoDB (local or cloud)
---

##npm
```bash
Setup
npm install
npm start

---

##🌱 Environment Variables

Create a .env file in the root directory:
```bash
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

---

##📈 Future Enhancements

Feedback analytics dashboard

Charts and reports

Pagination and filtering

Email notifications

Cloud deployment
---
##🎯 Learning Outcomes

React and modern JavaScript development

REST API design using Express.js

MongoDB integration with Mongoose

Secure authentication with JWT

Clean and scalable project architecture

---

##👨‍🎓 Author

Pushpam Kumar
Final Year B.Tech (Computer Science)
Frontend / Full-Stack Developer
