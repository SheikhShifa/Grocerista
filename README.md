## Grocerista
Grocerista is a comprehensive grocery management system designed to streamline operations for modern grocery stores. It provides a web-based application for customers to browse, shop, and purchase groceries, while administrators can manage products and inventory.

 ## Features
*Admin Panel* : Add, update, or delete products.
*Product Browsing* : Users can view products with detailed information.
*Cart Management*: Add products to a cart and proceed to checkout.
*Order Placement*: Fill in details like name, address, and complete the purchase.

## Technologies Used
*Frontend*: React, JavaScript, CSS
*Backend*: Spring Boot, Java
*Database*: MySQL
*Build Tools*: Maven
*API*: RESTful APIs

## Project Directory
```
grocerista/
│
├── backend/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   │   └── com/grocerista/
│   │   │   │       ├── controller/
│   │   │   │       ├── model/
│   │   │   │       ├── repository/
│   │   │   │       ├── service/
│   │   │   ├── resources/
│   │   │       ├── application.properties  # Spring Boot configuration
│   │   └── test/                           # Test cases for backend
│   └── pom.xml                             # Maven build configuration
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   │   ├── ProductList.js              # Component to list products
│   │   │   ├── Cart.js                     # Component for the shopping cart
│   │   │   ├── Checkout.js                 # Component for checkout process
│   │   ├── services/
│   │   │   └── ApiService.js               # Service to make API calls to the backend
│   │   ├── App.js                          # Main App component
│   └── package.json                        # Node.js dependencies
│
└── README.md                               # Project documentation
```
## Backend:
     a. Controller/: Handles incoming HTTP requests from the frontend.
     b. Service/: Business logic for managing products, orders, and more.
     c. Repository/: Handles database interactions (CRUD operations).
     d. Model/: Contains entity classes that represent database tables.
     e. application.properties: Configuration file for setting up the Spring Boot application, including database connections.

## Frontend:
     a. components/: Contains reusable React components for different UI features like Product List, Cart, and Checkout.
     b. services/ApiService.js: Manages API calls to the Spring Boot backend using Axios or the Fetch API.
     c. App.js: The main entry point for the React app, setting up routes and initializing components.
     
## Screenshots
1.![image](https://github.com/user-attachments/assets/62d5e684-1565-4837-ae6b-ebac2c3b588d)
2. ![image](https://github.com/user-attachments/assets/3938a5ce-ae19-44f9-8604-e070f1ecdec7)
3. ![image](https://github.com/user-attachments/assets/aa61c0ef-2ea7-4ded-b3c0-728a71e61973)
4. ![image](https://github.com/user-attachments/assets/1b12ba0d-9da1-43b7-9efa-865fc1f387dc)
5. ![image](https://github.com/user-attachments/assets/dcb105dc-d292-42ce-9f6d-7da783d970b6)
6. ![image](https://github.com/user-attachments/assets/649d6c2a-989b-4f51-863b-9f1462f6f3a8)
7. ![image](https://github.com/user-attachments/assets/edc1a0e3-2418-4bf0-a1b4-6c7b4d595a37)
8.![image](https://github.com/user-attachments/assets/37c7e358-a779-4172-ae41-1f7621ca8097)
9.![image](https://github.com/user-attachments/assets/0de8c5a7-90a1-45da-b385-1f8263c00cf1)
10.![image](https://github.com/user-attachments/assets/ad68365d-7f2a-464c-9553-baa899df4d12)
11.![image](https://github.com/user-attachments/assets/0f2a5e50-bea9-4483-b0ea-30ff4164c198)

```
NOTE :
1. Project - Spring boot backend folder need to install in Spring Tool Suite.
2. App - React front end folder need to install in Vs Code.
```
