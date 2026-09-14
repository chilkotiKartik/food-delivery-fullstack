<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:0F172A,50:1E293B,100:0F172A&text=Full-Stack%20Food%20Delivery%20Application&fontColor=FFFFFF&fontSize=36&fontAlignY=40&desc=Node.js%20%20Express%20%20React%20%20MongoDB%20%20Admin%20Portal%20%20REST%20API&descColor=94A3B8&descFontSize=15&descAlignY=62" width="100%" alt="Full-Stack Food Delivery Application" />

<br />

[![GitHub stars](https://img.shields.io/github/stars/chilkotiKartik/=for-the-badge&logo=github&color=1E293B)](https://github.com/chilkotiKartik/food-delivery-fullstack/stargazers)
[![License](https://img.shields.io/badge/License-MIT-0284c7?style=for-the-badge)](LICENSE)
[![Maintained](https://img.shields.io/badge/Maintained%3F-yes-10b981?style=for-the-badge)](https://github.com/chilkotiKartik/food-delivery-fullstack)
[![Author](https://img.shields.io/badge/Author-Kartik%20Chilkoti-6366f1?style=for-the-badge)](https://github.com/chilkotiKartik)

</div>

---

## 📌 Project Overview

An end-to-end full-stack food ordering platform featuring a customer-facing responsive menu, real-time cart and order placement, full-featured restaurant admin panel, and Express/MongoDB backend.

---

## 🚀 Key Features

- **Customer Storefront:** Dynamic menu browsing, category filtering, cart management, and order summary.
- **Admin Control Center:** Real-time dish management (Add/Edit/Remove items) and live order status updates (Food Processing, Out for Delivery, Delivered).
- **Secure REST Endpoints:** JWT-protected routes for order history and administrative controls.

---

## 🛠️ Architecture & Tech Stack

| Layer | Technologies |
| :--- | :--- |
| **Frontend Storefront** | React, CSS Modules / Tailwind, Axios |
| **Admin Dashboard** | React, Real-time status toggle, Image upload |
| **Backend REST API** | Node.js, Express.js, JWT Authentication |
| **Database** | MongoDB, Mongoose ODM, Cloudinary |

---

## 📂 Repository Structure

`	ext
food-delivery-fullstack/
??? backend/                # Express server, MongoDB models & API routes
??? frontend/               # Customer ordering storefront (React)
??? admin/                  # Restaurant management dashboard (React)
`

---

## ⚙️ Environment Configuration

Create a .env.local or .env file in the root directory:

`nv
PORT=4000
MONGODB_URI=mongodb+srv://user:pass@cluster.mongodb.net/food-del
JWT_SECRET=your_jwt_secret_key
`

---

## 🚦 Getting Started

### 1. Clone the Repository
`ash
git clone https://github.com/chilkotiKartik/food-delivery-fullstack.git
cd food-delivery-fullstack
`

### 2. Install Dependencies
`ash
npm install
`

### 3. Run Development Server
`ash
npm run dev
`

Open [http://localhost:3000](http://localhost:3000) in your browser to view the application.

---

## 👤 Author

**Kartik Chilkoti**
- **GitHub:** [@chilkotiKartik](https://github.com/chilkotiKartik)
- **Email:** [chilkotikartik@gmail.com](mailto:chilkotikartik@gmail.com)

---

<div align="center">
<sub>Engineered with precision by <strong>Kartik Chilkoti</strong> &bull; All rights reserved.</sub>
</div>