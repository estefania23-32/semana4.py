#Read.me

*************************************
##📦Inventory(supermarket la vaquita) 📦 |
*************************************
|These are the funtions of the program|
**************************************
1)Add products with name, price, and quantity
2)Search for products by name
3)Update product prices
4)Remove products from inventory
5)Calculate total inventory value
6)Requires minimum 5 products before exiting

***********************************************
Instructions for the correct use of the program :
***********************************************
 ## 🚀 How to Use
 1. Run the program with python inventory_system.py
2. Select options from the menu by entering a number (1-7)
3. Follow the prompts to manage your inventory
***********************************************
1)Add at least 5 products (required)
2)Search for specific products
3)Update prices that you nees change
4)Remove discontinued products
5)Calculate total inventory value
## 💡 Example Usage
===== INVENTORY LA VAQUITA =====
1. Add product
2. Search product
3. Update price
4. Remove product
5. Calculate total inventory value
6.Exit

Enter your choice (1-6): 1
Add product name: Leche
Enter product price: $2.500
Enter product quantity: 10
Product 'Leche' added successfully.

**********************************************
### Data Structure 📝                          |
**********************************************
This program uses Python's match-case statement
The main program loop runs until the user chooses to exit (option 6) 
and has sufficient inventory items.

The inventory is stored as a Python dictionary:
python
inventory = {
    "product_name": {
        "price": 10.99,
        "quantity": 25
    },
    # More products...
}
**********************************************
## 🔍 Error Handling                         |
**********************************************
The program includes validation to prevent:
 +Adding duplicate products
 + Entering non-numeric values for prices and quantities
 + Using negative or zero values for prices and quantities


