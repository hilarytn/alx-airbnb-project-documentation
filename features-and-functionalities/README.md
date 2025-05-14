# 🏡 Airbnb Clone – Backend Features and Functionalities

This document outlines the core **features and functionalities** supported by the backend of the Airbnb Clone project. It serves as a reference for developers, testers, and stakeholders.

---

## ✅ Core Functional Areas

### 1. User Management
- User registration (guest, host)
- Email verification
- Login/logout functionality
- JWT-based authentication
- Password hashing (e.g., bcrypt)
- Role-based access control (guest, host, admin)
- Profile updates
- Profile photo upload

---

### 2. Property Management (Host Role)
- Create, update, delete property listings
- Upload property images (local storage or cloud)
- Set price, availability, and location
- View all properties by a host
- Filter/search properties by location, price, availability, etc.

---

### 3. Booking System (Guest Role)
- Book available properties
- View upcoming and past bookings
- Cancel booking (within policy limits)
- Calculate total cost based on date range
- Booking status: `pending`, `confirmed`, `canceled`
- Host booking management (view who booked their property)

---

### 4. Payment Handling
- Create payment after booking confirmation
- Payment methods: Credit Card, PayPal, Stripe (ENUM)
- Track payment status and history
- Payment confirmation email

---

### 5. Reviews and Ratings
- Leave reviews on completed bookings
- 1–5 star rating system
- Comment field for additional feedback
- View average property rating

---

### 6. Messaging System
- User-to-user messaging (Guest ↔ Host)
- View inbox and sent messages
- Timestamps and content history

---

### 7. Notifications
- Email notifications for:
  - Successful booking
  - Payment confirmation
  - Cancellations
  - Messages

---

### 8. Admin Panel (Role: Admin)
- Manage users (activate/deactivate)
- Manage listings
- Moderate reviews and reported content
- View system logs and analytics (optional)

---

## 📄 Visual Summary

The feature map has been documented and exported as a PNG from Draw.io.

**File Location:**
