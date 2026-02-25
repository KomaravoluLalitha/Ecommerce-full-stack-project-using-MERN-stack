#  Full Stack MERN E-Commerce Application

##  Project Overview

This is a full-stack E-Commerce web application built using the MERN stack (MongoDB, Express, React, Node.js).

The application supports user authentication, product management, order processing, secure payments, image uploads, and admin controls.

The project is structured into three main modules:

- Frontend - User-facing shopping experience
- Backend - REST APIs and business logic
- Admin Panel - Product, order, and user management

---

##  Features

###  User Features

- User registration and login (JWT authentication)
- Browse products
- Add products to cart
- Secure checkout
- Online payments using Razorpay and Stripe
- Order history
- Product images stored via Cloudinary

###  Admin Features

- Admin authentication
- Add, update, and delete products
- Manage users
- Manage orders
- View sales and order details

###  Security

- JWT-based authentication
- Protected routes
- Secure payment gateways
- Environment variables for secrets

---

##  Tech Stack

### Frontend

- React.js
- HTML5, CSS3, JavaScript
- Axios
- React Router

### Backend

- Node.js
- Express.js
- MongoDB Atlas
- Mongoose
- JWT (JSON Web Tokens)

### Database

- MongoDB Atlas (Cloud Database)

###  Payment Gateways

- Razorpay
- Stripe

###  Image Upload

- Cloudinary

---

##  Project Structure
```
mern-ecommerce/
├── frontend/        # User-facing React application
├── admin/           # Admin panel (React)
├── backend/         # Node.js & Express backend
├── README.md
└── .env
```

---

##  Environment Variables

Create a `.env` file inside the backend folder and add:
```env
PORT=5000
MONGO_URI=your_mongodb_atlas_connection_string
JWT_SECRET=your_jwt_secret_key

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

RAZORPAY_KEY_ID=your_razorpay_key
RAZORPAY_KEY_SECRET=your_razorpay_secret

STRIPE_SECRET_KEY=your_stripe_secret
```

 Never push `.env` files to GitHub

---

##  How to Run the Project

### Clone the Repository
```bash
git clone <your-repo-url>
cd mern-ecommerce
```

### Backend Setup
```bash
cd backend
npm install
npm start
```

### Frontend Setup
```bash
cd frontend
npm install
npm start
```

### Admin Panel Setup
```bash
cd admin
npm install
npm start
```

---

##  Functionalities Implemented

- RESTful APIs
- CRUD operations
- Secure authentication
- Payment processing
- Cloud image management
- Role-based access (Admin/User)

---

##  Concepts Covered

- MERN full-stack development
- JWT authentication and authorization
- Payment gateway integration
- Cloud storage (Cloudinary)
- MongoDB Atlas
- Secure API handling
- Modular project architecture

---

##  Future Enhancements

- Product reviews and ratings
- Wishlist functionality
- Order tracking
- Email notifications
- Deployment on AWS, Render, or Vercel
- Advanced admin analytics dashboard

---

##  License

This project is developed for learning, portfolio, and demonstration purposes.

---