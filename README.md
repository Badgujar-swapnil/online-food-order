# The Online Food Order System

The **Online Food Order System** is a web application designed to manage food orders for both users and administrators. Built using **Spring Boot**, this system integrates various controllers to handle the functionalities efficiently.

## Key Features

### Admin Management:
- **Admin Registration & Login**: Admins can register and log in to the system. Upon successful login, they gain access to the **admin dashboard**.
- **Category Management**: Admins can add or delete food categories. Deleting a category automatically removes all associated food items.
- **Food Management**: Admins can manage food items by adding, updating, or deleting them. This includes uploading images and setting prices and discounts for each item.

### User Management:
- **User Registration & Login**: Users can sign up and log in to place orders. Password recovery is available via email and phone verification.
- **Cart Functionality**: Users can add food items to their cart and manage the contents before placing an order.
- **Order Placement**: Orders can be placed directly from the cart. Each order generates a unique **order ID**, and orders are tracked by their status (e.g., pending, delivered).
- **Order History**: Users can view their past orders and search for orders by ID or date.

### Food & Category Browsing:
- Users can browse food items by category or search for specific items by name.
- Individual food items can be viewed in detail, including descriptions, prices, and images.

### Order Management:
- **Order Tracking**: Users can place orders, which are stored with details like **order ID**, date, and delivery status.
- **Admin Order Management**: Admins can update the **delivery status** and **date** for each order.
## Screnshots
![Screenshot (56)](https://github.com/user-attachments/assets/623b9470-e21a-4dd7-8023-dd97b8ad770b)
![Screenshot (57)](https://github.com/user-attachments/assets/49e924f6-b795-4741-b3a7-a83ae6428b4b)

![Screenshot (58)](https://github.com/user-attachments/assets/704f5a56-7c4e-4ae2-8857-4ce9852684fe)
![Screenshot (55)](https://github.com/user-attachments/assets/eab14a74-48df-4ea8-bdc7-0cac6cf28bfb)
![Screenshot (60)](https://github.com/user-attachments/assets/5c710228-6d7f-4c3b-a6f9-12f1352e7c65)
![Screenshot (61)](https://github.com/user-attachments/assets/1dd90d07-673b-41b1-b9f7-0bb0ef9fe2d3)
## Technologies
- **Java**: A widely used object-oriented programming language, serving as the core of our system.
- **MySQL**: A relational database management system used for data storage.
- **JSP**: JavaServer Pages, used for rendering the frontend UI.
- **Spring Boot**: A Java framework that simplifies the development of stand-alone, production-grade Spring applications.

## Set Up Instructions for Running the Application

Follow these steps to set up and run the Online Food Order System with Spring Boot and MySQL:

### Prerequisites
- Java Development Kit (JDK) 11 or higher
- MySQL Server
- Maven (for dependency management)
### Step 1: Clone the Repository
-Clone the project repository to your local machine using the following command:
-```bash
-git clone https://github.com/Badgujar-swapnil/online-food-order-system.git
### Step 2:Step 2: Set Up MySQL Database
-Open MySQL Workbench or any MySQL client.
-Create a new database
### Step 3:Configure Application Properties
Open the src/main/resources/application.properties file and update the following properties:
spring.datasource.url=jdbc:mysql://localhost:3306/food_order_system

spring.datasource.username=your_mysql_username

spring.datasource.password=your_mysql_password

spring.jpa.hibernate.ddl-auto=update

spring.jpa.show-sql=true

### Step 4:Build Application through maven  tool
### Step 5:Run application 
- http://localhost:8080



