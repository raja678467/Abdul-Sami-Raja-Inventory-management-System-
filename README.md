# Inventory Management System

## Overview

The Inventory Management System is a Python-based console application designed to manage inventory efficiently. The system supports role-based access control, allowing administrators to manage products while regular users can only view and search products.

## Features

### User Authentication

* Secure login system with predefined users.
* Role-based access:

  * **Admin**: Full access to inventory management features.
  * **User**: Limited access to view and search products.

### Product Management (Admin Only)

* Add new products.
* Edit existing product details.
* Delete products from inventory.
* Adjust stock quantities.

### Inventory Operations

* View all available products.
* Search products by name or category.
* Low stock alerts for products below the threshold level.

## Technologies Used

* Python 3
* Object-Oriented Programming (OOP)

## Project Structure

```text
inventory_management_system.py
```

### Main Classes

* `User` - Stores user information and roles.
* `Product` - Stores product details.
* `InventoryManagementSystem` - Handles authentication and inventory operations.

## Default Login Credentials

### Admin Account

* Username: `admin`
* Password: `adminpass`

### User Account

* Username: `user`
* Password: `userpass`

## How to Run

1. Clone the repository:

```bash
git clone <repository-url>
```

2. Navigate to the project directory:

```bash
cd inventory-management-system
```

3. Run the application:

```bash
python inventory_management_system.py
```

## Sample Functionalities

* User Login
* Add/Edit/Delete Products
* Search Products
* Stock Adjustment
* Low Stock Notification

## Future Enhancements

* Database integration (SQLite/MySQL).
* Password encryption.
* Graphical User Interface (GUI).
* File handling for data persistence.
* Sales and purchase management.

## Author

Developed as a Python-based Inventory Management System project.
