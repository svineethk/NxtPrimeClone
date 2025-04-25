# 🛒 eCommerce Application – NxtPrime Clone

A modern eCommerce web application with user authentication, protected routes, and complete cart & product management.

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

## 🛠️ Installation & Setup

### 📥 Clone the Repository
```bash
git clone https://github.com/svineethk/NxtPrimeClone.git


### 🌐 Access the App
Once the server starts, open your browser and navigate to:

http://localhost:3000
