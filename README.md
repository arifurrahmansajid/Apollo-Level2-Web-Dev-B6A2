# Vehicle Rental System

**Live Deployment:** https://assignment-02-alpha-eight.vercel.app/

## 🎯 Project Overview

A backend API for a vehicle rental management system that handles:
- **Vehicles** - Manage vehicle inventory with availability tracking
- **Customers** - Manage customer accounts and profiles
- **Bookings** - Handle vehicle rentals, returns and cost calculation
- **Authentication** - Secure role-based access control (Admin and Customer roles)

## 🛠️ Technology Stack

- **Node.js** + **TypeScript**
- **Express.js** (web framework)
- **PostgreSQL** (database)
- **bcrypt** (password hashing)
- **jsonwebtoken** (JWT authentication)

## 🎯 Features

### 🔐 Authentication & Roles
- JWT-based signin
- Password hashing with bcrypt
- Role based autorization
    - `Admin` -> Full access
    - `Customer` -> Can register, browse vehicles and can manage their own bookings



