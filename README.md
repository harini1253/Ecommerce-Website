# 🧾 Trendify — Modern MERN E-commerce Platform

Welcome to **Trendify**, a fast, scalable, and fully-featured e-commerce application built with the **MERN stack**. This project showcases real-world features you'd expect from an online store — product listings, authentication, admin tools, cart and checkout system — all wired together with MongoDB, Express, React, and Node.js.
---

## 📦 What's Inside?

| Feature                | Description                                            |
|------------------------|--------------------------------------------------------|
| 🧑 User Accounts        | Register, Login, Logout, JWT-secured sessions         |
| 🛒 Shopping Cart        | Persistent cart across sessions                       |
| 🧑‍💼 Admin Panel         | Add/edit/delete products, manage users                |
| 💰 Stripe Checkout      | Secure payments with Stripe API                       |
| ☁️ Cloudinary Support   | (Optional) Image upload and CDN hosting               |
| 📱 Responsive UI        | Built for all screens with modern React/Vite setup    |

---

## 🛠 Tech Stack

**Frontend:** React + Vite + Tailwind CSS  
**Backend:** Node.js + Express.js  
**Database:** MongoDB Atlas  
**Auth:** JWT (with roles)  
**Payments:** Stripe  
**Image Upload:** Cloudinary (optional)  

---
##.env
PORT=4000
MONGO_URI=mongodb+srv://username:password@cluster.mongodb.net/dbname
JWT_SECRET=your_secret_key
STRIPE_SECRET_KEY=your_stripe_key
ADMIN_EMAIL=admin@example.com
ADMIN_PASSWORD=admin123
---
Running the App
Start backend server:
cd backend
npm run server

Start frontend development server:
cd frontend
npm run dev

✅ Admin Test Login
Email: admin@example.com
Password: admin123

