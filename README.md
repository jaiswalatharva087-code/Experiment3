# FBS E-Books Website

A lightweight, static front-end web application for an online e-books store. This project demonstrates core web development concepts, responsive layouts using CSS Flexbox, and client-side form validation using vanilla JavaScript.

## ✨ Features

- **Home Page:** Landing page with promotional banners, discounts, and navigation links.
- **Login Page:** Login form with JavaScript validation for required fields.
- **Registration Page:** Registration form with validation for:
  - Username length
  - Password strength
  - Email format
  - 10-digit phone number
  - Gender selection
  - Languages known
  - Address input
- **Shopping Cart:** Cart interface with product pricing and quantity validation.
- **Form Validation:** Client-side validation using vanilla JavaScript.
- **Responsive Design:** CSS Flexbox layouts for organized and adaptable page structures.

## 🛠️ Technologies Used

- **HTML5** – Web page structure
- **CSS3** – Styling, Flexbox layouts, and responsive design
- **JavaScript** – Client-side form validation and input handling

## 📁 Project Structure

```text
FBS-E-Books-Website/
├── index.html          # Home page
├── login.html          # User login page
├── registration.html   # User registration page
├── cart.html           # Shopping cart page
├── styles.css          # Styling and responsive layouts
├── fbs.png             # Website logo
└── README.md           # Project documentation
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser
- Visual Studio Code (optional)

### Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/fbs-ebooks-website.git
   ```

2. Navigate to the project directory:

   ```bash
   cd fbs-ebooks-website
   ```

3. Open `index.html` in your browser.

   Alternatively, use the **Live Server** extension in Visual Studio Code.

## ✅ Validation Logic

The application uses vanilla JavaScript to validate user inputs.

- **`validateLogin()`** – Checks required login fields.
- **`validate()`** – Validates registration details, including username, password, email, phone number, and selections.
- **`validateCart()`** – Ensures cart quantities are valid positive integers.

## 🔮 Future Enhancements

- Integrate a backend for user authentication.
- Connect a database such as MySQL or MongoDB.
- Add dynamic cart totals and quantity updates.
- Integrate a payment gateway such as Razorpay or Stripe.

## 📄 License

This project is open-source. Add a `LICENSE` file to specify the license under which the project is distributed.
