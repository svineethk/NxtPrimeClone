# 🛒 NxtPrime Clone – A Modern eCommerce Web App

A fully functional eCommerce application built with React, featuring user authentication, protected routes, product filtering, and full cart management.

---

## 🚀 Features

### 🔐 User Authentication
- **Login credentials**:
  - **Username:** `rahul`
  - **Password:** `rahul@2021`
- Authenticated users are redirected to the **Home** page.
- Invalid credentials display an appropriate error message.

### 🔒 Protected Routes
- Routes like **Home**, **Products**, and **Cart** are protected.
- Unauthenticated users are redirected to the **Login** page when attempting to access protected pages.

### 🛍️ Product Management
- Products are fetched from `productsApiUrl`.
- Users can:
  - Search by product name
  - Filter by **category** or **rating**
  - Clear filters to reset the view
- A loading spinner appears while fetching data.

### 📦 Product Details Page
- Displays full product details fetched from `productDetailsApiUrl`.
- Users can:
  - View product quantity
  - Update quantity using "+" and "–" icons

### 🛒 Cart Management
- Add products to the cart (authenticated users only)
- Update item quantities
- Remove individual items or clear the entire cart
- View:
  - Total item count
  - Total price
- Cart state is managed using **React Context (CartContext)**

---

## 🧰 Tech Stack

- React
- React Router
- Context API
- Express JS
- JavaScript (ES6+)
- HTML5 & CSS3

---

## 🛠️ Installation & Setup

### 📥 Clone the Repository
```bash
git clone https://github.com/svineethk/NxtPrimeClone.git
```

📦 Installation

Using npm:
```bash
npm install
```

Or using yarn:
```bash
yarn install
```


🚀 Running the App

Using npm:
```bash
npm start
```

Or using yarn:
```bash
yarn start
```

🌐 Access the App
Once the server starts, open your browser and navigate to:

```bash
http://localhost:3000
```
