# JKart – JavaScript E-Commerce Application

## Description

JKart is designed as a learning project to practice frontend development skills, simulate e-commerce functionality, and understand the workflow of an interactive web application without relying on a backend.

JKart is a frontend-only e-commerce web application built using HTML, CSS, and JavaScript.
It simulates a real-world online shopping experience, allowing users to register, log in, browse products, add items to a cart, and manage purchases.

This project demonstrates key JavaScript concepts such as DOM manipulation, event handling, localStorage management, conditional rendering, and API integration. It is designed as a learning project for practicing frontend development and understanding the workflow of an interactive web application without a backend.

Users can:
- Register with email and password (with duplicate email validation)
- Log in and log out securely
- Browse products dynamically fetched from an external API
- Add products to their cart and manage quantities
- View real-time cart total and remove items
- Persist data across browser sessions using localStorage

## Live Demo
https://priyanka-0001.github.io/JKart-Ecommerce/

---

## Project Screenshots

### Home Page
![Homepage](assets/homepage.png)

### Login Page
![Login](assets/login.png)

### Register Page
![Register](assets/register.png)

### Cart Page
![Cart](assets/cart.png)

---

## Features

User Authentication
- User registration with duplicate email check
- Duplicate email validation
- Login with credential verification
- Logout functionality

Product System
- Product data fetched from external API
- Dynamic product display
- Add to Cart functionality

Cart System
- Increase/decrease product quantities
- Remove product from cart
- Grand total calculation
- Empty cart message

State Management
- Data persistence using browser localStorage
- Cart count updates in real time
- Track logged-in user

---

## Technologies Used

HTML5 – Page structure  
CSS3 – Styling and layout  
JavaScript (ES6) – Application logic  
Fetch API – Retrieving product data  
localStorage – Client-side data persistence

---

## Key Concepts Used

- DOM Manipulation  
- Event Handling  
- Array methods (`find`, `filter`, `some`)  
- JSON.parse() and JSON.stringify()  
- localStorage CRUD operations  
- Conditional rendering  
- API fetching  
- Page-based logic execution

---

## Project Structure

JKart/
│
├── index.html
│
├── html/
│   ├── login.html
│   │── register.html
│   └── cart.html
│
├── css/
│   ├── homepage.css
│   ├── login.css
│   ├── register.css
│   └── cart.css
│
├── js/
│   └── jkart.js
│
├── assets/
│    ├── cart.png
│   ├── flowchart.png
│   ├── homepage.png
│   ├── login.png
│   └── register.png
│
└── README.md
    
---

## Installation/Setup

1. Clone the repository:
    git clone https://github.com/Priyanka-0001/JKart-Ecommerce.git
2. Open index.html in your browser.
3. No backend or server is required; it runs entirely in the browser.
4. Optional: Deploy to GitHub Pages for a live demo.

---

## How to Use

1. Open homepage.
2. Register a new account or login with existing credentials.
3. Browse products and add to cart.
4. Navigate to Cart page to modify quantities or remove items.
5. Click Checkout to confirm order and clear cart.

---

## Application Flowchart

![Flowchart](assets/flowchart.png)

---

## Application Flow

1. User Registration
    → Enter user details → Email duplicate check → Save user data in localStorage  

2. User Login
    → Validate credentials → Store logged-in user in localStorage → Redirect to homepage  

3. Product Listing
    → Products fetched from DummyJSON API → Displayed on homepage  

4. Cart System
    → Add items to cart → Update quantities → Remove items → Calculate grand total  

5. Checkout
    → Order confirmation → Cart cleared  

---

## Future Improvements

- Backend integration 
- User-specific cart system  
- Order history feature  
- Payment gateway integration  
- Improved UI animations  

---
