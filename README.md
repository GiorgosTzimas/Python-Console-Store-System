# Python-Console-Store-System

This project is a text-based store management system built in Python. It simulates a simple online shop where users can browse products, place orders, manage a shopping cart, and perform administrative actions.

The project was developed as part of academic coursework for the course Programming, Algorithms and Data Structures (MSc. in Business Administration and Data Science).

---

## Features

### User functionality
- View full product catalog
- Search products by ID or name (linear search)
- Add and remove items from cart
- Apply discount codes
- Checkout with basic order confirmation

### Admin functionality
- Add new products
- Remove existing products
- Update product price, size, and stock
- Simple password-protected access

---

## Key Concepts

- Object-Oriented Programming (OOP)
  - Classes, inheritance, abstraction
- Data structures
  - Lists and dictionaries for catalog and orders
- Algorithms
  - Linear search for product lookup
- Input validation and user interaction
- Modular program structure

---

## Project Structure

The system is built around the following components:

- `Display`  
  Handles product visualization and search

- `Product`  
  Admin-level operations for managing the catalog

- `Order`  
  Handles product selection and order creation

- `Shopping_Cart`  
  Extends order functionality with discounts and checkout

- Global catalog and order storage  
  Used to simulate a simple backend system

---
