# 📨 Message App – Backend

This is the backend for the Messaging Slack Clone built using Node.js and Express. It handles user authentication, real-time messaging via WebSockets, file uploads to AWS S3, and persistent chat history using MongoDB.

---

## 🔧 Features

- RESTful APIs for Authentication, Channels & Workspaces
- WebSocket (Socket.IO) for Real-time Messaging
- File Uploads to AWS S3
- MongoDB for Chat & User Data Persistence
- Cross-Origin Resource Sharing (CORS) configured
- JWT-based Authentication Middleware

---

## 🚀 Tech Stack

- Node.js
- Express.js
- MongoDB & Mongoose
- Socket.IO
- AWS SDK (S3)
- dotenv
- CORS
- bcrypt & JWT

---

## ⚙️ Setup Instructions

# Navigate to the backend folder
cd backend

# Install dependencies
npm install

# Start the development server
npm start

Environment Configuration
Create a .env file in the root directory with the following variables:
PORT=3000,
MONGO_URI=your_mongo_connection_string,
JWT_SECRET=your_jwt_secret,
AWS_ACCESS_KEY_ID=your_aws_access_key,
AWS_SECRET_ACCESS_KEY=your_aws_secret_key,
S3_BUCKET_NAME=your_bucket_name

### ESLint & Prettier Setup

Check out this helpful guide:  
[Setting up ESLint and Prettier in a Node.js Project](https://medium.com/@sindhujad6/setting-up-eslint-and-prettier-in-a-node-js-project-f2577ee2126f)







