# ⚡ ElectroCart – MERN Stack E-Commerce Application

ElectroCart is a full-stack **electronics e-commerce platform** built using the **MERN stack (MongoDB, Express, React, Node.js)**.  
It supports product browsing, search, cart management, authentication, admin controls, and order processing.

This project is built as a **real-world portfolio application** demonstrating modern web development practices.

---

## 🧩 Project Description

ElectroCart allows users to browse electronic products, search by keywords, add items to cart, and place orders.  
Admins can manage products, users, and orders through a secure admin dashboard.

---

## 🧱 Folder Structure Description

### Root Directory
- **backend/** – Handles all server-side logic, APIs, database models, and authentication
- **frontend/** – Contains the React application and UI logic
- **uploads/** – Stores uploaded product images
- **.env.example** – Template for environment variables
- **package.json** – Project dependencies and scripts
- **README.md** – Project documentation

---

### Backend Folder (`/backend`)
- **config/** – Database connection configuration
- **controllers/** – Business logic for routes
- **data/** – Sample seed data for products and users
- **middleware/** – Authentication and error handling middleware
- **models/** – MongoDB schemas (User, Product, Order)
- **routes/** – Express API routes
- **server.js** – Backend entry point

---

### Frontend Folder (`/frontend`)
- **public/** – Static assets
- **src/**
  - **actions/** – Redux action creators
  - **constants/** – Redux constants
  - **reducers/** – Redux reducers
  - **components/** – Reusable UI components
  - **screens/** – Application screens (pages)
  - **App.js** – Main React component
  - **index.js** – React DOM entry point

---

## 🚀 Features

### User Features
- User registration & login
- JWT authentication
- Product browsing & search
- Shopping cart
- Order placement
- User profile management
- Order history

### Admin Features
- Admin authentication
- Product CRUD operations
- User management
- Order management
- Image uploads

---

## 🛠 Tech Stack

### Frontend
- React.js
- Redux
- React-Bootstrap
- Axios
- React Router

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT
- Multer

---

## ⚙️ Environment Setup

Create a `.env` file in the root directory using `.env.example`.

---

## 🌐 Application URLs

- Frontend: `http://localhost:3000`
- Backend API: `http://localhost:5000`

---

## 👤 Author

**Shriraksha Kulkarni**  
GitHub: https://github.com/raksha408

---

## 📄 License

This project is for educational and portfolio purposes.
