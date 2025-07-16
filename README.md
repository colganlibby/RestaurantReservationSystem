# 🍽️ Restaurant Reservation & Ordering System

A full-stack restaurant management web application developed as part of my **Advanced Web Programming** module at Cardiff Metropolitan University. This system enables customers to browse menus, reserve tables, order food, apply discount codes, and securely pay using Stripe. Staff and admin users have dedicated dashboards to manage orders, bookings, and content in real time.

---

## 🎯 Project Overview

This was created as a **graded university assignment** focused on applying real-world full-stack development techniques. Emphasis was placed on usability, security, and modular structure — delivering a practical solution that reflects how a restaurant could operate online.

---

## 💻 Features

### 👤 Customer
- Register / log in with secure authentication
- Browse a dynamic menu pulled from the database
- Add items to a cart (with quantity & promo code support)
- Reserve tables with server-side time slot validation
- Pay securely through Stripe Checkout
- Receive email + on-screen confirmations
- View current and past reservations

### 🛠️ Admin & Staff
- Admin dashboard with:
  - Menu management (Add/Edit/Delete)
  - Reservation tracking & cancellation
  - Sales reporting (total income, orders)
  - Admin logs with timestamped activities
- Staff dashboard to:
  - View customer orders
  - Update order statuses

---

## 🧰 Tech Stack

- **Frontend:** HTML, CSS
- **Backend:** PHP
- **Database:** MySQL
- **Payment Processing:** Stripe Checkout API
- **Security:** Session handling, password hashing, role-based access control

---

## 📁 Folder Structure
├── admin/ # Admin-only tools
├── customer/ # Customer dashboard, cart & bookings
├── staff/ # Staff-facing order updates
├── includes/ # Shared PHP functions & DB connection
├── payments/ # Stripe API integration
├── index.php # Landing/Login page
└── db.sql # Database schema
