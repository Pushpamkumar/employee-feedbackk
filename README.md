Employee Feedback Dashboard

A full-stack web application designed to digitize and streamline employee feedback collection. The system replaces unstructured manual feedback processes with a secure, scalable, and well-organized digital solution.

📌 Project Overview

The Employee Feedback Dashboard enables employees to submit feedback through a user-friendly interface while allowing administrators to securely manage, review, and analyze feedback. The application focuses on clean UI design, secure authentication, and modular backend architecture.

🚀 Features
👨‍💼 Employee Features

Submit feedback easily through a responsive UI

View previously submitted feedback

Secure login using authentication

🛠️ Admin Features

View and manage all employee feedback

Delete or review feedback entries

Role-based access control

⚙️ System Features

Full CRUD operations for feedback management

RESTful APIs for frontend–backend communication

Secure authentication using JWT

Modular and scalable backend structure

Responsive design for multiple screen sizes

🧑‍💻 Tech Stack
Frontend

React.js

JavaScript (ES6+)

HTML5

CSS3 / Tailwind CSS

Backend

Node.js

Express.js

Database

MongoDB

Mongoose (ODM)

Authentication

JSON Web Tokens (JWT)

Tools

Git

GitHub

VS Code

dotenv

🏗️ Project Structure
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

🔐 Authentication & Security

Implemented JWT-based authentication

Protected API routes using middleware

Role-based access control for Admin and Employee

Environment variables secured using .env

⚙️ Installation & Setup
Prerequisites

Node.js

MongoDB (local or cloud)

npm

Backend Setup
npm install
npm start

Environment Variables

Create a .env file in the root directory:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

🧪 API Functionalities

Create employee feedback

Fetch feedback (admin / employee)

Delete feedback

User authentication & authorization

Secure REST endpoints

📈 Future Enhancements

Feedback analytics and reports

Admin dashboard with charts

Pagination and advanced filtering

Email notifications

Deployment on cloud platform

🎯 Learning Outcomes

Practical experience with React and modern JavaScript

Backend development using Node.js and Express

REST API design and implementation

Secure authentication using JWT

Database integration using MongoDB

Clean and scalable project architecture

👨‍🎓 Author

Pushpam Kumar
Final Year B.Tech (Computer Science)
Frontend / Full-Stack Developer
