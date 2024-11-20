**Application Features Overview**

 * Username: rahul
 * Password: rahul@2021

This eCommerce application implements user authentication, protected routes, and various product management features.

   * Login: Users can log in with the following credentials:

   * After successful login, they are redirected to the Home Route. Invalid credentials trigger an error message.

   * Protected Routes: Unaunthenticated users are redirected to the Login Route when trying to access protected routes like Home, Products, or Cart.

   * Product Listing: Products are fetched using the productsApiUrl with filters like title, category, and rating. A loader is displayed while fetching data. Users can search, filter by category or rating, and clear filters to reset the view.

   * Product Item Details: Users can view detailed information of a product, including its quantity, and can update the quantity using plus and minus icons. HTTP requests are made to the productDetailsApiUrl to fetch product details.

   * Cart Management: Authenticated users can add products to the cart, update quantities, remove items, and clear all cart items. The total amount and item count are displayed on the Cart Route, and the cart is managed using CartContext.

Installation 

Clone the repository:
   git clone [https://github.com/your-username/ecommerce-app.git](https://github.com/svineethk/NxtPrimeClone.git)

Navigate to the project directory:
   cd ecommerce-app

Install dependencies:
  If you're using npm:
   npm install
  Or, if you're using yarn:
   yarn install

Start the development server:
  If you're using npm:
   npm start
  Or, if you're using yarn:
   yarn start

**This will start the application in development mode, and you can view it by navigating to http://localhost:3000.**
