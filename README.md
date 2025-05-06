# mobi_e_commerce
🛒 Commerce Platform Project - MERN Stack
Welcome to the eCommerce Platform Project built using the MERN (MongoDB, Express.js, React, Node.js) Stack. This project delivers a robust and full-featured online shopping platform with many functionalities to enhance the user experience.

🚀 Live App Demo
🔗 https://mern-shop-abxs.onrender.com/

⚠️ Note: Render's free tier shuts down after 15 minutes of inactivity. The first request after reactivation may be slow.

✨ Features
Full-Featured Shopping Cart: Add, remove, and manage products.

Product Reviews and Ratings: Leave feedback and ratings.

Top Products Carousel: Highlights top-rated items.

Product Pagination: Efficient navigation.

Product Search: Keyword-based search.

User Profile & Orders: View and track order history.

Admin Dashboard: Manage products, users, and orders.

Manage Admins

Manage Products (Add/Edit/Delete)

Manage Users

Detailed Order Info

Mark Orders as Delivered

Checkout Process: With shipping & payment method options.

Razorpay Integration: Secure payment processing.

Database Seeder: Populate with sample users/products.

🧰 Getting Started
✅ Prerequisites
Fork and clone the repo:

bash
git clone https://github.com/your-username/MERN-eCommerce.git
cd MERN-eCommerce
Set up MongoDB (MongoDB Atlas recommended).

Create Razorpay and Brevo (email) accounts.

🔐 Environment Variables
Rename .env.example to .env and add the following:

env
NODE_ENV=development
PORT=5000
JWT_SECRET=ADD_YOUR_JWT_SECRET_HERE
MONGO_URI=ADD_YOUR_MONGO_URI_HERE
RAZORPAY_KEY_ID=ADD_YOUR_RAZORPAY_KEY_ID
RAZORPAY_KEY_SECRET=ADD_YOUR_RAZORPAY_KEY_SECRET
PAGINATION_MAX_LIMIT=12
EMAIL_HOST=smtp-relay.brevo.com
EMAIL_PORT=587
EMAIL_USER=ADD_YOUR_BREVO_LOGIN
EMAIL_PASS=ADD_YOUR_BREVO_PASSWORD
EMAIL_FROM=ADD_YOUR_BREVO_LOGIN
📦 Install Dependencies
bash
# Root dependencies
npm install

# Frontend dependencies
cd frontend
npm install
▶️ Run the App
Run both frontend and backend:
bash
npm run dev
Run only backend:
bash
npm run server
🏗️ Build & Deploy
To create a production build:

bash
cd frontend
npm run build
🌱 Seed Database
bash
# Import data
npm run data:import

# Destroy data
npm run data:destroy
🔑 Sample User Logins
🔐 Admin Login
https://mern-shop-abxs.onrender.com/admin/login

Email: admin@admin.com

Password: admin123

👤 Customer Logins
https://mern-shop-abxs.onrender.com/login

John Doe

Email: john@email.com

Password: john123

Alice Smith

Email: alice@email.com

Password: alice123

