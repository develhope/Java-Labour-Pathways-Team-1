## Warehouse

Write a program in Java for warehouse management.

- The program should read multiple input strings that contain the products to be stored. (Use Scanner)
- The products can be of three types: tablet, smartphone, notebook.
- For each product (whether it is a tablet, smartphone, or notebook) we will have a series of attributes:
  - The type of device (tablet, smartphone, or notebook)
  - The manufacturer of the device
  - The model of the device
  - The optional description of the device
  - The display size
  - The storage size
  - The purchase price
  - The selling price
  - The device ID that uniquely represents the device in the warehouse.
- The program must have cart management where the user can add a device to the cart, removing it from the list of devices currently in the warehouse when the sale operation is completed.
  It is suggested to use keyboard input for selecting the operations to perform (1. add to warehouse, 2. unload goods from warehouse, 3. create cart, 4. add item to cart, etc.)

### The program must have a series of methods:
#### Each method should return the list of devices resulting from the search or an error if the search does not produce results.

- A method to print all devices in the warehouse.
- A method that allows searching by device type.
- A method that allows searching by manufacturer.
- A method that allows searching by model.
- A method that allows searching by selling price.
- A method that allows searching by purchase price.
- A method that allows searching within a certain price range (e.g., from 150.00 to 250.00 euros).
- A method that calculates the average purchase expense per device and returns the average value.
- A method to add an item to the cart by ID with the corresponding warehouse update that will return the updated cart.
- A method to remove an item from the cart by ID with the corresponding warehouse update that will return the updated cart.
- A method that calculates the total of the cart and returns this value.
- A method that finalizes the sale operation and permanently removes the items from the warehouse and deletes the cart itself.

---
