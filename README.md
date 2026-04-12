# simple-procurement-inventory-management-system
📦 Simple Inventory Management System (Python)
A beginner–intermediate Python project that demonstrates how to build a console‑based inventory management system using dictionaries, functions, and a menu‑driven interface.
This project is perfect for learning:

Data structures (dictionaries, lists)

Functions and modular code design

Loops and user input handling

CRUD operations (Create, Read, Update, Delete)

Basic business logic (stock value, pricing updates)

🚀 Features

✔ Add new items
Users can add new products with quantities, base prices, and sale prices.

✔ View all items
Displays the full inventory in a clean, readable format.

✔ Search for an item
Quickly check if a product exists and view its details.

✔ Update item quantity
Increase stock levels for existing products.

✔ Update item prices
Adjust the base price and sale price for any product.

✔ Remove an item
Delete a product from the inventory.

✔ View total stock value
Calculates the total value of all items based on sale price × quantity.

✔ Menu‑driven interface
Runs in a loop until the user chooses to exit.

🧠 How It Works
The inventory is stored as a Python dictionary:

python
inventory = {
    
    # [quantity, base_price, sale_price]
    
    'milk': [29, 33.0, 37.89],
    'bread': [15, 22.88, 30.0],
    'sweets': [15, 2.09, 5.99],
    'sugar': [20, 15.78, 22.0],
    'ginger biscuits': [22, 10.0, 15.82]}
    
Each product contains:

Quantity:	Number of units in stock

Base Price:	Cost price per unit

Sale Price:	Selling price per unit

The program uses functions to keep the code modular and readable.
A while True loop displays a menu and calls the appropriate function based on user input.

📋 Menu Options
Code
1. Update item quantity
2. Update item price
3. Exit

🛠 Technologies Used
Python 3

Console input/output

Dictionaries & lists

Functions and loops


📂 Project Structure

inventory_system.py

README.md
