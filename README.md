# E-commerce Product API
This project is an E-commerce API built using Django and Django REST Framework. The API provides functionality to manage products, categories, and user accounts for an e-commerce platform. It includes user authentication, CRUD operations for products, and a search feature.

Features
1. Product Management (CRUD)
Create, Read, Update, Delete operations for managing products.
Each product includes:
Name
Description
Price
Category
Stock Quantity
Image URL
Created Date
Validation for required fields like Name, Price, and Stock Quantity.
2. User Management (CRUD)
CRUD operations for users who manage the products.
User attributes include:
Username
Email
Password
Authentication system to secure endpoints.
3. Product Search
Search for products by Name or Category.
Flexible search allowing partial matches in product names.
Pagination for search results to handle large datasets efficiently.
4. Product Viewing
Retrieve a list of products or view product details.
Filter products by Category, Price Range, or Stock Availability.
5. Authentication
User authentication using Django’s built-in authentication system.
Optional token-based authentication using JWT (JSON Web Tokens).
