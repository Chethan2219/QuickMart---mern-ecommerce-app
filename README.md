# QuickMart - MERN ECommerce App

Welcome to **QuickMart**, a fully-featured e-commerce web application built using the **MERN** (MongoDB, Express.js, React, Node.js) stack. This project demonstrates the development of a complete e-commerce platform including features like product listing, cart, user authentication, admin dashboard, product management, and checkout process.

> ⚙️ Author: **Chethan T**

---

## 🌐 Tech Stack

- **Frontend:** React, Redux, React Router, Axios, Bootstrap
- **Backend:** Node.js, Express.js, MongoDB, JWT, Multer
- **Database:** MongoDB (local/cloud)
- **Dev Tools:** ESLint, Babel, Git, GitHub
- **Deployment:** Heroku-ready

---

## 📚 Features You Will Learn

### Frontend (React)

- React Components, Props, Events, Hooks
- React Router for navigation
- Axios for API communication
- Redux for state management
- Rating and review system
- Responsive UI design using Flexbox & Grid

### Backend (Node + Express)

- Express routing & middleware
- MongoDB data handling via Mongoose
- RESTful APIs for products, users, and orders
- JWT-based Authentication and Authorization
- File upload with Multer (local & AWS S3)
- Secure environment management with dotenv

### Admin Dashboard

- Create, update, delete products
- Upload product images
- Manage user accounts
- Manage orders and deliveries
- View sales summary

---

## 🚀 Quick Start (Local Setup)

### 1. Clone the repository

     git clone https://github.com/your-username/quickmart-mern-ecommerce.git
     cd quickmart-mern-ecommerce

### 2. Install MongoDB

      Install MongoDB locally or connect to a cloud MongoDB Atlas instance.

### 3. Run Backend Server

      npm install
      npm start

### 4. Run Frontend React App

  # In a new terminal
    cd frontend
    npm install
    npm start
    
👨‍💻 Admin Access
To create admin user, visit:

    http://localhost:5000/api/users/createadmin
    
Use the returned email and password to login:

    http://localhost:3000/signin

🛠️ Development Progress Summary
✅ Core Pages
    Home Page with Product List
    Product Details Page
    Shopping Cart Page
    User Sign In / Register Page
    Shipping, Payment, and Order Placement
    Order History & Details
    Admin Product / Order Management

✅ Advanced Features
    JWT-based protected routes
    Order and payment summary
    Product ratings & user reviews
    Product filtering & sorting
    Upload product images (Local & AWS S3 support)

🖼️ Image Upload Feature
  Local Server Upload
      Uses multer to store files locally.
      Endpoint: POST /api/uploads

  AWS S3 Upload (Optional)
    Uses aws-sdk and multer-s3
    Requires AWS credentials in .env file:

      AWS_ACCESS_KEY_ID=yourAccessKey
      AWS_SECRET_ACCESS_KEY=yourSecretKey
      
🧾 File Structure

    quickmart-mern-ecommerce/
    ├── backend/
    │   ├── models/
    │   ├── routes/
    │   ├── controllers/
    │   ├── utils/
    │   └── server.js
    ├── frontend/
    │   ├── components/
    │   ├── screens/
    │   ├── redux/
    │   └── App.js
    └── README.md

🧪 Key Libraries Used
    express, mongoose, jsonwebtoken, bcryptjs
    axios, react-redux, redux-thunk, react-router-dom
    multer, aws-sdk, dotenv

⚙️ Environment Variables
  Create .env files in both root and frontend if needed.
  Backend .env:
  
      MONGODB_URL=mongodb://localhost/quickmart
      JWT_SECRET=yourSecretKey
      PORT=5000
      AWS_ACCESS_KEY_ID=yourKey (optional)
      AWS_SECRET_ACCESS_KEY=yourSecret (optional)

  👤 Author
      • Name: Chethan T
      • Project: QuickMart – MERN ECommerce App

  🙌 Acknowledgements
      Inspired by modern shopping platforms and community-driven open-source projects.
