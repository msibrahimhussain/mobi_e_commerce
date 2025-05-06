<<<<<<< HEAD
# eCommerce Platform Project - MERN Stack

Welcome to the eCommerce Platform Project built using the MERN (MongoDB, Express.js, React, Node.js) Stack. This project provides a robust and full-featured online shopping platform with various functionalities to enhance the user experience.

**Live App Demo** : [https://mern-shop-abxs.onrender.com/](https://mern-shop-abxs.onrender.com/)</br>
Note: Please be aware that Render's free tier will automatically shut down after 15 minutes of inactivity. Consequently, the first request after reactivation may experience a delay, but subsequent requests will be faster.

## Features

- **Full-Featured Shopping Cart**: Seamless shopping cart functionality for users to add, remove, and manage products.
- **Product Reviews and Ratings**: Users can leave reviews and provide ratings for products.
- **Top Products Carousel**: Display a carousel of top-rated or featured products.
- **Product Pagination**: Navigate through products efficiently with pagination.
- **Product Search Feature**: Easily search for products based on keywords.
- **User Profile with Orders**: Users can create profiles and track their order history.
- **Admin Dashboard**: Comprehensive dashboard for administrators to manage admins, products, users, and orders.
- **Admin Admin Management**: Manage admin accounts.
- **Admin Product Management**: Add, edit, and delete products from the platform.
- **Admin User Management**: Manage user accounts.
- **Admin Order Details Page**: Access detailed information about each order.
- **Mark Orders as Delivered Option**: Ability to update order status to "delivered."
- **Checkout Process**: Seamless checkout with options for shipping and payment methods.
- **Razorpay Integration**: Secure payment processing through Razorpay.
- **Database Seeder**: Easily populate the database with sample products and users.

## Getting Started

### Prerequisites

1. Fork the repository to your GitHub account.
2. Clone the forked repository to your local machine

```bash
git clone https://github.com/your-username/MERN-eCommerce.git
```

```bash
cd MERN-eCommerce
```

3. Create a MongoDB database and obtain your MongoDB URI from [MongoDB Atlas](https://www.mongodb.com/cloud/atlas).
4. Create a Razorpay account and obtain your Key ID and Key Secret from [Razorpay](https://razorpay.com/).
5. Create a Brevo account and generate a new SMTP Key from [Brevo](https://www.brevo.com/)

### Env Variables

1. Rename the `.env.example` file to `.env` and add the following environment variables:

```dotenv
=======
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
>>>>>>> 686cdd5f102058a1a379c83036d38aca60a59ef0
NODE_ENV=development
PORT=5000
JWT_SECRET=ADD_YOUR_JWT_SECRET_HERE
MONGO_URI=ADD_YOUR_MONGO_URI_HERE
<<<<<<< HEAD
RAZORPAY_KEY_ID=ADD_YOUT_RAZORPAY_KEY_ID
RAZORPAY_KEY_SECRET=ADD_YOUR_RAZORPAY_KEY_SECRET
PAGINATION_MAX_LIMIT=12 # This will show 12 products per page; you can change it.
=======
RAZORPAY_KEY_ID=ADD_YOUR_RAZORPAY_KEY_ID
RAZORPAY_KEY_SECRET=ADD_YOUR_RAZORPAY_KEY_SECRET
PAGINATION_MAX_LIMIT=12
>>>>>>> 686cdd5f102058a1a379c83036d38aca60a59ef0
EMAIL_HOST=smtp-relay.brevo.com
EMAIL_PORT=587
EMAIL_USER=ADD_YOUR_BREVO_LOGIN
EMAIL_PASS=ADD_YOUR_BREVO_PASSWORD
EMAIL_FROM=ADD_YOUR_BREVO_LOGIN
<<<<<<< HEAD
```

### Install Dependencies

Run the following commands to install dependencies for both the frontend and backend:

```bash
npm install
cd frontend
npm install
```

### Run

To run both the frontend and backend concurrently, use:

```bash
npm run dev
```

To run only the backend:

```bash
npm run server
```

## Build & Deploy

To create a production build for the frontend:

```bash
cd frontend
npm run build
```

## Seed Database

Use the following commands to seed the database with sample users and products, or destroy all data:

```bash
=======
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
>>>>>>> 686cdd5f102058a1a379c83036d38aca60a59ef0
# Import data
npm run data:import

# Destroy data
npm run data:destroy
<<<<<<< HEAD
```

## Sample User Logins

- **Live Admin Dashboard Login:**: [https://mern-shop-abxs.onrender.com/admin/login](https://mern-shop-abxs.onrender.com/admin/login)

  - Email: admin@admin.com
  - Password: admin123

- **Live Customer Logins:**: [https://mern-shop-abxs.onrender.com/login](https://mern-shop-abxs.onrender.com/login)
  - John Doe
    - Email: john@email.com
    - Password: john123
  - Alice Smith
    - Email: alice@email.com
    - Password: alice123
