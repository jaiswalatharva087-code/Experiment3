# FBS e-Books Website

This project is a small, static front-end for an online bookstore called FBS. It contains pages for a home screen, login, registration, and a sample shopping cart. The pages are built with HTML and use JavaScript for basic client-side form validation.

## Pages

- **Home (`index.html`)** – Introduces the FBS e-Books website and advertises discounts. It links to the login, registration, and cart pages.
- **Login (`login.html`)** – Provides username and password fields. JavaScript checks that both fields are filled in before allowing submission.
- **Registration (`registration.html`)** – Collects a username, password, email, phone number, gender, known languages, and address. JavaScript checks the required fields and basic input formats before showing a registration-success message.
- **Cart (`cart.html`)** – Displays two sample books, their prices, preset quantities, and a displayed total. JavaScript checks that each quantity is a positive whole number when the form is submitted.

## Running the site

Open `index.html` in a web browser. Use the navigation links to move between the pages. No build step or server is required for this static demo.

## Current scope

The pages demonstrate a basic bookstore interface and browser-side validation only. They do not connect to a backend, authenticate users, save registration details, process payments, or recalculate cart prices and totals when quantities change.
