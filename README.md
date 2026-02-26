🛍️ ShopEZ – One Stop Shop for Online Purchases

A full-stack MERN E-commerce Platform with multi-role access (Customer, Vendor, Admin), secure JWT authentication, Razorpay payment integration, and scalable MongoDB architecture.

📌 Introduction
📖 Project Title

ShopEZ: One-Stop Shop for Online Purchases

👥 Team Members
Name	Role
Thathireddy Lokitha	Full Stack Developer (Frontend & Backend)
Yadavakunta Pradeep Reddy	Full Stack Developer (Frontend & Backend)
M Sai Dhiraj Kumar	Database & Payment Integration
🚀 Features
🔐 Authentication

User Registration & Login

JWT Token Authentication

Password hashing using bcrypt

Role-Based Access (Customer / Vendor / Admin)

Protected API Routes

📦 Product Management

Add / Update / Delete Products

Product Listing & Details

Search & Category Filtering

🛒 Cart Management

Add to Cart

Update Quantity

Remove Items

Real-time Total Calculation

📦 Order Management

Create Order

Order History

Status Tracking

💳 Payment Integration

Razorpay Order Creation

Payment Verification

Success / Failure Handling

👨‍💼 Admin Panel

Manage Users

Manage Vendors

Manage Products

Monitor Orders

Dashboard Analytics

🏗️ Architecture
🎨 Frontend

React.js

Vite

Tailwind CSS

React Router v6

Axios

Context API

⚙️ Backend

Node.js

Express.js

MongoDB Atlas

Mongoose

JWT

Bcrypt

Razorpay SDK

🗄️ Database Collections

Users

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
├── backend/
│   ├── src/
│   │   ├── controllers/
│   │   ├── models/
│   │   ├── routes/
│   │   ├── middlewares/
│   │   ├── utils/
│   │   └── config/
│   ├── server.js
│   └── package.json
│
├── frontend/
│   ├── src/
│   │   ├── pages/
│   │   │   ├── admin/
│   │   │   ├── vendor/
│   │   │   ├── user/
│   │   │   ├── auth/
│   │   │   └── help/
│   │   ├── components/
│   │   ├── api/
│   │   ├── context/
│   │   └── App.jsx
│   ├── package.json
│   └── vite.config.js
│
└── Documentation/
⚙️ Installation & Setup
🔹 Backend
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

Backend → http://localhost:5000

🔹 Frontend
cd frontend
npm install
npm run dev

Frontend → http://localhost:5173

🔐 User Roles
Role	Access
Customer	Browse, Cart, Orders
Vendor	Product & Order Management
Admin	Full Platform Control
🔒 Security

JWT Authentication

Role-Based Access Control

Password Hashing (bcrypt)

Protected API Endpoints

Error Handling Middleware

📱 Responsive Design

Tailwind CSS

Mobile-first approach

Optimized for all screen sizes

🧪 Testing

Postman API Testing

Manual UI Testing

Payment Flow Verification

📄 License

This project is developed for educational purposes.

👨‍💻 Project Status

✅ Completed
✅ Production Ready
✅ Multi-Role E-Commerce Platform
