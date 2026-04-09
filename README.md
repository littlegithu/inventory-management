# Inventory Management System

A simple JavaScript project for managing a product inventory array. This project demonstrates basic array manipulation using functions to add, update, and remove items.

##  Features

*   **View Inventory:** Access the first item in the list.
*   **Add Products:** Dynamically push new items to the inventory.
*   **Update Records:** Modify existing product names by their index.
*   **Remove Items:** Delete the most recently added product.

##  File Structure

*   `inventoryManagement.js`: Core logic and array manipulation functions.

##  Usage

The system manages a `products` array. Use the following functions to interact with it:


| Function | Description |
| :--- | :--- |
| `logFirstProduct()` | Logs the item at index `0` to the console. |
| `addProduct(name)` | Adds a new item to the end of the array. |
| `updateProductName(index, name)` | Updates the product name at a specific index. |
| `removeLastProduct()` | Removes the last item from the array. |

### Example Code
```javascript
// Initial inventory: ["Laptop", "Phone", "Headphones", "Monitor"]

addProduct("Tablet"); 
// Result: ["Laptop", "Phone", "Headphones", "Monitor", "Tablet"]

updateProductName(1, "Smartphone"); 
// Result: ["Laptop", "Smartphone", "Headphones", "Monitor", "Tablet"]

removeLastProduct(); 
// Result: ["Laptop", "Smartphone", "Headphones", "Monitor"]
