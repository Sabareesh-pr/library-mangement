# Bookstore Library & Stock-Keeping App

A full-stack web application for managing book rentals and inventory, developed during a one-month internship at **ICT Academy, Technopark Phase 1, Trivandrum**. The app leverages the **MERN stack** to provide seamless functionalities for both **users** and **admins**, streamlining book rental processes and inventory management.

---

## Table of Contents

- [Executive Summary](#executive-summary)
- [Introduction](#introduction)
- [Features](#features)
  - [User Features](#user-features)
  - [Admin Features](#admin-features)
- [Objectives](#objectives)
- [Scope and Deliverables](#scope-and-deliverables)
- [Technology Stack](#technology-stack)
- [Methodology](#methodology)
- [Pages and Functionality](#pages-and-functionality)
  - [User View](#user-view)
  - [Admin View](#admin-view)
- [Requirements](#requirements)
---

## Executive Summary

The project focuses on creating a **Bookstore Library App** that allows users to rent books, avoiding the inconvenience of visiting a physical library. Admins can efficiently manage rentals, track users, and send notifications. This hands-on experience with **full-stack development** emphasized front-end responsiveness, back-end API creation, and database integration.

---

## Introduction

Existing systems for managing book rentals often rely on manual processes, leading to inefficiencies. This project aimed to address these challenges by creating a fully digital solution using the **MERN stack**. The app provides two distinct user roles:

- **Users:** Can browse, like, and send rental requests for books.
- **Admins:** Manage book inventories, track rentals, and control user access.

This modern, web-based solution offers a user-friendly and efficient platform for library and inventory management.

---

## Features

### User Features

- **Registration and Login:** Users can sign up and manage their profiles.
- **Book Catalog:** Browse and view book details.
- **Rental Requests:** Send requests for books.
- **Profile Management:** Update user profiles and track rental history.

### Admin Features

- **Admin Dashboard:** Manage users and books with CRUD operations.
- **User Control:** Block or delete user access.
- **Rental Tracking:** Monitor book statuses (rented or available).
- **Notifications:** Send overdue notifications via email.

---

## Objectives

1. Develop a responsive, user-friendly web application.
2. Enhance skills in full-stack development using the **MERN stack**.
3. Automate book rental processes and inventory management.
4. Deliver a robust application within a tight timeline.

---

## Scope and Deliverables

### Scope

1. Build a fully functional web application for book rentals.
2. Implement user authentication and profile management.
3. Provide admin capabilities to manage users and books.

### Deliverables

1. **Pages:**
   - Login/Signup (User) and Login (Admin)
   - Home Page (Book Catalog)
   - Book Details Page
   - User Profile Management
   - Admin Dashboard
2. **Database:**
   - Book details, user profiles, and rental data storage.

---

## Technology Stack

- **Frontend:** React.js
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT (JSON Web Tokens)
- **Hosting:** Cloud-based (e.g., AWS, Heroku)

---

## Methodology

We followed the **Agile Methodology** for this project:

1. **Requirement Analysis:** Gathered functional requirements.
2. **System Design:**
   - Created wireframes for interfaces.
   - Designed database schemas.
3. **Development:**
   - Built a responsive UI with React.js.
   - Developed RESTful APIs using Node.js and Express.js.
   - Integrated MongoDB for efficient data storage.
4. **Testing:** Conducted unit, functional, and user acceptance testing.
5. **Deployment:** Deployed the app to a live environment.

---

## Pages and Functionality

### User View

1. **Login/Sign Up Page:**
   - Collect user details (Name, Age, Email, etc.).
   - Successful login redirects to the **Home Page**.
2. **Home Page:**
   - Displays 20 random books with clickable details.
3. **Book Details Page:**
   - Includes Title, Author, Genre, ISBN, and Availability Status.
   - Allows liking and rental requests.
4. **Profile Page:**
   - Update user details and view rental history.
5. **Logout:**
   - Provides a secure logout option.

### Admin View

1. **Admin Login:**
   - Predefined credentials for admin access.
2. **Admin Dashboard:**
   - View, update, and manage book statuses.
   - Add, edit, or delete books.
   - Manage users (block or delete).
3. **Logout:**
   - Secure exit for admins.

---

## Requirements

### General Requirements

- Navbar with navigation to Home, Login/Logout.
- Responsive design for enhanced user experience.

### User Pages

1. Login/Sign Up
2. Home Page
3. Book Details Page
4. Profile Management Page

### Admin Pages

1. Admin Dashboard
2. Book Management
3. User Management
