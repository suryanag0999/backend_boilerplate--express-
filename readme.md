# Node.js + Express + MongoDB Boilerplate

This is a basic backend boilerplate using **Node.js**, **Express**, and **MongoDB (Mongoose)**. It provides a clean folder structure with routing, controllers, models, middleware, and MongoDB configuration. Use it as a starting point for building any RESTful API or MERN stack project.

---

## 🗂️ Folder Structure

backend/
├── utils/ # Database connection

├── controllers/ # Route logic (business logic)

├── middleware/ # Custom middleware (auth, error handling)

├── models/ # Mongoose models

├── routes/ # API route definitions

├── .env # Environment variables

├── index.js # Entry point

└── package.json


## ⚙️ Getting Started

### 1. Clone this Repo  

Initialize npm (if not done)
npm init -y


## Install Dependencies
npm install express mongoose dotenv


## Install nodemon for automatic reloads (development only)
npm install --save-dev nodemon

## Create a .env file
PORT=5000

MONGO_URI=mongodb://localhost:27017/yourdbname

JWT_SECRET=yourSuperSecret


## Add start scripts in package.json

"scripts": {
  "start": "node index.js",
  
  "dev": "nodemon index.js" 
}

## ▶Run the App
For development (auto-reload) //automatic reloads
npm run dev



📌 Notes
This is a starter template, modify and expand based on your project needs.
Includes sample:
User model
User registration/login routes
Basic error handling middleware

 Customize As Needed
Feel free to replace the sample User route/controller/model with your own. This structure is flexible and easy to scale for small to medium APIs and full-stack applications.
