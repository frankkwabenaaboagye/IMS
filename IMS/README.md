# Inventory Management System

## Overview
Top-down and bottom-up approaches for an inventory management system. 
Testing the high-level functionality of order processing with bottom-up assembled modules like 
product service and shopping cart, initially using stubs for external systems (e.g., payment gateway). 
Replacing stubs with real integrations.


## Project Structure

```plaintext
src/main/java/com/inventory
├── config
├── controller
├── dto
├── model
├── repository
├── service
│   ├── stubs
│   └── real
└── utils