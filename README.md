🛒 Online Second-Hand Marketplace
📌 Project Overview

The Online Second-Hand Marketplace is a web-based application that allows users to buy and sell second-hand products through a secure and user-friendly digital platform. The system is designed to simplify peer-to-peer resale of unused items such as electronics, books, furniture, and accessories while promoting reuse and sustainability.

This project is developed as part of an academic course project using modern full-stack web technologies.

🎯 Objectives

Provide a simple platform for buying and selling used products

Enable secure user authentication and role-based access

Allow sellers to list products with images and descriptions

Allow buyers to browse and search available products

Promote sustainable consumption and reduce waste

🧰 Technology Stack

Frontend:

React.js

HTML5, CSS3, JavaScript

Responsive UI design

Backend:

Node.js

Express.js

RESTful APIs

Database:

MongoDB

Mongoose ODM

Authentication & Utilities:

JWT (JSON Web Token)

Multer (for image upload)

bcrypt (password hashing)

⚙️ Features

User registration and login

Secure authentication using JWT

Product listing with image upload

Browse and search products

User dashboard for managing listings

Profile management

Role-based access control

Responsive design for all devices

🏗️ System Architecture

The application follows a client–server architecture:

React frontend handles UI and user interaction

Node.js + Express backend manages APIs and business logic

MongoDB stores user and product data

Communication occurs via HTTP/HTTPS using REST APIs

📁 Project Structure
project-root/
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── config/
│   └── server.js
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
└── README.md

▶️ How to Run the Project
Prerequisites

Node.js installed

MongoDB installed and running

Code editor (VS Code recommended)

Steps

Clone the repository

git clone <your-github-repo-link>


Start Backend

cd backend
npm install
npm start


Start Frontend

cd frontend
npm install
npm start


Open browser and visit:

http://localhost:3000

🔒 Non-Functional Features

Secure authentication and data protection

Responsive and user-friendly UI

Scalable architecture

Modular and maintainable codebase

🚀 Future Enhancements

Online payment gateway integration

Real-time chat between buyer and seller

Product recommendation system

Admin panel with advanced controls

Order and delivery tracking

🎓 Academic Note

This project is developed for academic and learning purposes only.
Client proofs, payment handling, and logistics are not included in the current scope.

👨‍💻 Author

Name: Aditya Bhardwaz
Project Type: Academic Project
Course: Web Development / Full Stack Development

📄 License

This project is intended for educational use only.
