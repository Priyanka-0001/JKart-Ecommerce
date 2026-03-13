# JKart – JavaScript E-Commerce Application

## Overview
JKart is a frontend-only e-commerce web application built using HTML, CSS, and JavaScript.  
The application allows users to register, login, browse products, add items to a cart, and manage their cart.

The project focuses on practicing **core JavaScript concepts such as DOM manipulation, event handling, API integration, and localStorage data management**.

---

## Live Demo
https://priyanka-0001.github.io/JKart-Ecommerce/

---

## Features

User Authentication
- User registration
- Duplicate email validation
- Login with credential verification
- Logout functionality

Product System
- Product data fetched from external API
- Dynamic product display
- Add to Cart functionality

Cart System
- Quantity increase/decrease
- Remove product from cart
- Grand total calculation
- Empty cart message

State Management
- Data persistence using browser localStorage
- Cart count updates in real time
- Logged-in user tracking

---

## Technologies Used

HTML5 – Page structure  
CSS3 – Styling and layout  
JavaScript (ES6) – Application logic  
Fetch API – Retrieving product data  
localStorage – Client-side data persistence

---

## Project Structure
JKart/
│
├── index.html
├── login.html
├── register.html
├── cart.html
│
├── Homepage.css
├── Login.css
├── Register.css
├── Cart.css
│
├── JKart.js
│
└── README.md

---

## Application Flow

1. User Registration
    → Enter user details  
    → Email duplicate check  
    → Save user data in localStorage  

2. User Login
    → Validate credentials  
    → Store logged-in user in localStorage  
    → Redirect to homepage  

3. Product Listing
    → Products fetched from DummyJSON API  
    → Displayed on homepage  

4. Cart System
    → Add items to cart  
    → Update quantities  
    → Remove items  
    → Calculate grand total  

5. Checkout
    → Order confirmation  
    → Cart cleared  

---

## Key JavaScript Concepts Used

- DOM Manipulation  
- Event Handling  
- Array methods (`find`, `filter`, `some`)  
- JSON.parse() and JSON.stringify()  
- localStorage CRUD operations  
- Conditional rendering  
- API fetching  
- Page-based logic execution

---

## Future Improvements

- Backend integration (Node.js / Express)  
- User-specific cart system  
- Order history feature  
- Payment integration  
- Improved UI animations  

---
