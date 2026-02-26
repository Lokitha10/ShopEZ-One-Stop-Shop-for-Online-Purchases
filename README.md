🛍️ ShopEZ – One Stop Shop for Online Purchases

A full-stack E-commerce platform built using the MERN Stack with multi-role access (Customer, Vendor, Admin), secure authentication, and Razorpay payment integration.

📌 1. Introduction
📖 Project Title

ShopEZ: One-Stop Shop for Online Purchases

👥 Team Members & Roles
Name	Role
Thathireddy Lokitha	Full Stack Developer (Backend & Frontend)
Yadavakunta Pradeep Reddy	Full Stack Developer (Backend & Frontend)
M Sai Dhiraj Kumar	Database & Payment Integration
🎯 2. Project Overview
✅ Purpose

Develop a secure ecommerce web app using MERN stack

Provide smooth online shopping experience

Implement JWT-based authentication

Manage products, cart, and orders efficiently

Integrate Razorpay payment gateway

Build scalable architecture using MongoDB Atlas

🎯 Goals

Fully functional full-stack ecommerce system

Secure role-based authentication

Product search & filtering

Cart & order processing

Admin management dashboard

Maintainable and scalable system design

🚀 3. Features & Functionalities
🔐 Authentication

User Registration with validation

JWT-based secure login

Password hashing using bcrypt

Role-based access (Customer / Vendor / Admin)

Profile management

Protected API routes

📦 Product Management

Add / Update / Delete products (Vendor/Admin)

View product listing & details

Category filtering

Search functionality

🛒 Cart Management

Add to cart

Update quantity

Remove items

Real-time total calculation

Cart persistence

📦 Order Management

Create order from cart

Unique order ID generation

Store order details

Order history

Status tracking

💳 Payment Processing

Razorpay order creation

Payment verification

Success / Failure handling

Order payment status update

👨‍💼 Admin Features

Admin login

Vendor verification

User management

Product & order monitoring

Analytics dashboard

Permission-based access control (22 permissions)

🏗️ 4. Architecture
🎨 Frontend

Tech Stack:

React.js

Vite

Tailwind CSS

Axios

React Router v6

Context API

Architecture Highlights:

Component-based reusable structure

Protected & role-based routes

Token stored in localStorage

REST API integration

Responsive mobile-first design

⚙️ Backend

Tech Stack:

Node.js

Express.js

MongoDB Atlas

Mongoose

JWT

Bcrypt

Razorpay SDK

Layered Architecture:

Server Layer (Express server)

Route Layer (Auth, Product, Cart, Order, Payment, Admin)

Controller Layer (Business logic)

Middleware Layer (JWT Auth, RBAC, Error handling)

Database Layer (MongoDB Atlas collections)

🗄️ Database Collections

Users

Admin

Vendors

Customers

Products

Orders

Cart

Wishlist

Reviews

Payments

📁 Project Structure
shopez/
│
├── backend/                        # Node.js / Express API
│   ├── src/
│   │   ├── controllers/            # Business logic
│   │   ├── models/                 # MongoDB schemas
│   │   ├── routes/                 # API endpoints
│   │   ├── middlewares/            # Auth & error handling
│   │   ├── utils/                  # Helper functions
│   │   └── config/                 # DB configuration
│   ├── server.js                   # Entry point
│   └── package.json
│
├── frontend/                       # React (Vite) App
│   ├── src/
│   │   ├── pages/
│   │   │   ├── admin/
│   │   │   ├── vendor/
│   │   │   ├── user/
│   │   │   ├── auth/
│   │   │   └── help/
│   │   ├── components/             # Reusable UI components
│   │   ├── api/                    # Axios API services
│   │   ├── context/                # React Context
│   │   └── App.jsx
│   ├── package.json
│   └── vite.config.js
│
└── Documentation/                  # Project docs
⚙️ Installation & Setup
🔹 Prerequisites

Node.js 16+

MongoDB Atlas account

npm

🔹 Backend Setup
cd backend
npm install

Create .env file:

MONGODB_URI=your_connection_string
JWT_SECRET=your_secret_key
PORT=5000
RAZORPAY_KEY_ID=your_key
RAZORPAY_KEY_SECRET=your_secret

Run backend:

npm start

Backend runs at:
http://localhost:5000

🔹 Frontend Setup
cd frontend
npm install
npm run dev

Frontend runs at:
http://localhost:5173

🔐 Authentication & Roles
Role	Access
Customer	Browse, Cart, Orders
Vendor	Manage products & orders
Admin	Full platform control
📊 Admin Dashboard

Vendor verification

User metrics

Product inventory overview

Order monitoring

Permission-based stats

🔒 Security Features

JWT authentication

Role-Based Access Control (RBAC)

Password hashing (bcrypt)

Protected API routes

Input validation

Error handling middleware

📱 Responsive Design

Mobile-first approach

Tailwind CSS

Optimized for all screen sizes

🧪 Testing

API tested using Postman

Manual frontend testing

Order & payment flow verification

🐛 Troubleshooting

Backend issues:

npm cache clean --force
rm -rf node_modules package-lock.json
npm install

Frontend issues:

rm -rf node_modules package-lock.json
npm install
📄 License

This project is developed for educational and demonstration purposes.

👨‍💻 Project Status

✅ Complete
✅ Production Ready
✅ Multi-role E-commerce Platform
