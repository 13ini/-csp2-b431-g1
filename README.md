<h1> Capstone2-Ecommerce API </h1>


TEAM MEMBER:
Bini Manandhar <br>
Prativa Gautam

**Project Overview**  
This project is part of Capstone 2, focused on developing user, product, cart, and order management features. The application enables users to register, authenticate, and manage profiles, while also offering a comprehensive product management system. Additionally, it includes cart and order functionalities, allowing users to add products to their cart and view order details.

**User Management Features**  
- **User Registration**: Allows new users to sign up for an account.  
- **User Authentication**: Enables users to log in and receive an authentication token.  
- **Admin Role Assignment**: Admins can elevate a standard user to an admin role.  
- **Profile Management**: Users can view and manage their profile details.  
- **Password Update**: Users can update their password securely.

**Product Management Features**  
- **Create Product (Admin only)**: Admins can add new products to the system.  
- **View All Products (Admin only)**: Admins can see all products listed in the system.  
- **View Active Products**: Any user can browse through all currently active products.  
- **View Product Details**: Anyone can access the details of a specific product.  
- **Update Product (Admin only)**: Admins can modify the details of existing products.  
- **Archive Product (Admin only)**: Admins can deactivate a product, marking it as inactive.  
- **Activate Product (Admin only)**: Admins can reactivate previously archived products.

**Cart Management Features**  
- **View Cart**: Users can see the items currently in their cart.  
- **Add to Cart**: Users can add products to their cart.  
- **Item Subtotal Calculation**: Displays the subtotal for each item in the cart.  
- **Cart Total Calculation**: Shows the total price for all items in the cart.  
- **Update Quantities**: Users can adjust the quantity of items in their cart.  
- **Remove Items**: Users can remove products from their cart.  
- **Clear Cart**: Users can empty their cart entirely.

**Order Management Features**  
- **Checkout**: Users can place an order based on the contents of their cart.  
- **View Orders**: Logged-in users can view all orders they’ve placed.  
- **Admin Order Management**: Admins can view all orders placed by all users.

**How to Run the Project**  
1. Clone the repository.  
2. Run `npm install` to install the necessary dependencies.  
3. Set up a `.env` file with the required environment variables.  
4. Start the server with `nodemon index.js`.  
5. Access the application via `http://localhost:4444`.

**Environment Variables**  
Create a `.env` file in the project root and include:  
- `MONGO_URI`: Your MongoDB connection string.  
- `JWT_SECRET`: A secret key for signing JWT tokens.



CSP-2 Group1

Prativa's work:
-Data Model Design
-User registration 
-User authentication 
-Retrieve User Details
-Set user as admin(Admin Only)
-Update password


Bini's work:
-Retrive Cart workflow
-Add to cart workflow
-Updated Product Quantity Workflow
-Remove from cart workflow
-Clear cart workflow
