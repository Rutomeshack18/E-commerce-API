# E-commerce Product API

## Overview

The E-commerce Product API is a backend service developed using Django and Django REST Framework. It provides a set of RESTful APIs for managing products in an e-commerce application, including functionalities for user authentication, product management, and category management.

## Features

- **User Authentication**: Implemented using JWT (JSON Web Tokens) for secure access.
- **Product Management**: CRUD operations (Create, Read, Update, Delete) for products.
- **Category Management**: Manage product categories.
- **CORS Support**: Allows cross-origin requests for client applications.
- **Custom Permissions**: Fine-grained access control for different user roles.

## Technologies Used

- **Django**: A high-level Python web framework for rapid development.
- **Django REST Framework**: A powerful toolkit for building Web APIs.
- **PostgreSQL**: A robust database management system.
- **Django CORS Headers**: A Django app to handle CORS (Cross-Origin Resource Sharing).
- **Django REST Framework Simple JWT**: A JSON Web Token authentication system for Django REST Framework.

## Requirements

- Python 3.x
- Django
- Django REST Framework
- PostgreSQL
- Django CORS Headers
- Django REST Framework Simple JWT
- Whitenoise (for serving static files in production)

## Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/yourusername/ecommerce-product-api.git
   cd ecommerce-product-api
