FBS e-Books Website

A lightweight, static front-end web application for FBS (Online E-Books Store). This project demonstrates core web development concepts, responsive layout structures using Flexbox, and client-side form validation using vanilla JavaScript.

📌 Features

Home Page (index.html): Welcoming landing page featuring promotional banners, discounts, and navigation links.

User Login (login.html): Simple user login interface with JavaScript validation ensuring non-empty input fields.

Registration Form (registration.html): Multi-field form featuring robust validation for:

Username (minimum length requirement)

Password strength validation

Regex-based Email format checks

10-digit Phone Number validation

Radio button selection (Gender)

Checkbox selection (Languages Known)

Address text area validation

Shopping Cart (cart.html): Interactive cart layout displaying items, pricing, and dynamic quantity check validation (ensuring positive whole numbers).

Responsive Layout (styles.css): Utilizes modern CSS Flexbox model (container1, container2, wrapper) for layout structuring.

📁 Repository Structure

├── index.html        # Main landing page
├── login.html        # User login page with JS validation
├── registration.html # User registration form with advanced JS validation
├── cart.html         # Sample shopping cart interface
├── styles.css        # CSS stylesheets for layout and design
├── fbs.png           # Logo asset
└── README.md         # Project documentation


🚀 Getting Started

Prerequisites

No backend server, package manager (like npm), or complex build tools are required to run this project. All you need is a modern web browser.

How to Run Locally

Clone the Repository:

git clone https://github.com/your-username/fbs-ebooks-website.git


Navigate to the Project Directory:

cd fbs-ebooks-website


Open in Browser:

Double-click index.html to open it directly in your default browser.

Alternatively, open it via a local extension such as VS Code's Live Server.

🛠️ Validation Logic Overview

The application incorporates vanilla JavaScript functions directly within HTML pages to handle form user experience and input integrity:

validateLogin(): Ensures required user credentials are submitted prior to form submission.

validate() (Registration): Validates input length, regex pattern matching for emails, numerical check (isNaN) for phone numbers, and radio/checkbox selections.

validateCart(): Ensures cart quantities are non-negative, non-zero integers before dynamic cart updates.

🎯 Future Enhancements & Scope

Currently, this project functions as a static front-end prototype. Future updates could include:

Integrating a backend (Node.js/Express, Python/Django, or PHP) for authentication and dynamic database support.

Connecting a database (MySQL, MongoDB) to dynamic user data and real-time product catalogs.

Adding dynamic total updates using JS DOM manipulation in the cart without needing page reloads.

Integrating payment gateways (Stripe, Razorpay) for full checkout workflows.

📄 License

This project is open-source and available under the M
