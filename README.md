#The Online Food Order System
is a web application designed to manage food orders for users and administrators. The application is built using Spring Boot and integrates various controllers to handle the functionalities of the system.

Key Features:
Admin Management:

Admin Registration & Login: Admins can register and log in to the system. Upon successful login, they can access the admin dashboard.
Category Management: Admins can add or delete food categories. Deleting a category also removes all associated food items.
Food Management: Admins can add, update, or delete food items, including uploading images and setting prices and discounts.
User Management:

User Registration & Login: Users can register and log in to place orders. Password recovery is available through email and phone verification.
Cart Functionality: Users can add food items to their cart and manage the cart's contents.
Order Placement: Users can place orders from their cart, generating a unique order ID. Orders are tracked by their status (e.g., pending, delivered).
Order History: Users can view their past orders and search for orders by ID or date.
Food & Category Browsing:

Users can browse food items by category and search for specific food items by name.
Individual food details can be viewed, including descriptions, prices, and images.
Order Management:

Users can place orders, which are stored in the system with details such as order ID, date, and delivery status.
Admins can update the delivery status and date for orders.
