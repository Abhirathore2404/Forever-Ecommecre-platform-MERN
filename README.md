<div align="center">


  <h1 align="center">Forever | E-Commerce Solution | MERN Stack</h1>

  <p align="center">
    A complete e-commerce solution with user authentication, product management, a shopping cart, and an admin dashboard. Built for performance and a smooth user experience.
    <br />
    <a href="[LINK_TO_YOUR_REPO]"><strong>Explore the Docs »</strong></a>
    <br />
  </p>
</div>
<br/>

---

### ✨ Key Features

* ✅ **Secure Authentication:** Robust user login and registration system.
* ✅ **Product Management:** Full product search, category filters, and an intuitive shopping cart and checkout flow.
* ✅ **Admin Dashboard:** A comprehensive dashboard for managing site inventory and users.
* ✅ **Modern Tech:** Built with RESTful APIs, proper validations, and protected routes.
* ✅ **Stunning UI/UX:** Responsive design coupled with GSAP, ScrollTrigger, and Locomotive Scroll for smooth, engaging animations.
* ✅ **High Performance:** Optimized API calls and MongoDB queries for speed.
* ✅ **Cloud Ready:** Uses MongoDB Atlas for the database and is deployed on Render for seamless hosting.

---

### 🛠️ Built With

This project leverages a modern and powerful tech stack:

| Frontend | Backend | Database & Cloud |
|---|---|---|
| ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) | ![NodeJS](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white) | ![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white) |
| ![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white) | ![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white) | ![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=for-the-badge&logo=cloudinary&logoColor=white) |
| ![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=for-the-badge&logo=greensock&logoColor=white) | ![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white) | ![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=white) |

---

## 🚀 Getting Started

This guide will get you a local copy of the project up and running.

### Prerequisites

First, ensure you have **Node.js** installed on your system. [cite_start]If not, you can download it from the [official website](https://nodejs.org/en/download/)[cite: 5].

### 🔑 Environment Setup

Before running the application, you need to set up your environment variables.

1.  Navigate to the `backend` folder.
2.  Create a new file named `.env`.
3.  Copy the following variables into the file and replace the placeholder values with your actual credentials.

```env
# Server Configuration
JWT_SECRET="example"
ADMIN_EMAIL="admin@example.com"
ADMIN_PASSWORD="example123"

# MongoDB Connection
MONGODB_URI="<-- Paste Your Mongo URI Here -->"

# Cloudinary Credentials (for image storage)
CLOUDINARY_API_KEY="<-- Paste Cloudinary API key -->"
CLOUDINARY_SECRET_KEY="<-- Paste Cloudinary SECRET key -->"
CLOUDINARY_NAME="<-- Paste Cloudinary cloud name -->"

# Payment Gateway Keys (Optional)
STRIPE_SECRET_KEY="<-- Paste Stripe Secret key -->"
RAZORPAY_KEY_SECRET="<-- Paste Razorpay Secret key -->"
RAZORPAY_KEY_ID="<-- Paste Razorpay key Id -->"
