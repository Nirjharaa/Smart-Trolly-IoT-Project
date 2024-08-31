**Automatic Billing Shopping Cart Using RFID
Overview**
This project automates the billing process in a supermarket by using an RFID-based system. Each item in the store is tagged with an RFID, and when the item is added to the cart, its corresponding price is displayed on an LCD screen, and the total bill is updated automatically. The system is built using an Arduino Nano, an LCD display, RFID tags, and a reader.

**Components Used**
1. Arduino Nano: The microcontroller that serves as the brain of the project, managing the input and output operations.
2. RFID Tags & Reader: RFID tags are attached to each item, and the reader detects the items when they are added to the cart.
3. 16x2 LCD Display: Displays item information like name, price, and total cost.
4. LEDs: Indicate whether an item has been successfully added (green) or if it is not recognized (red).
5. Buzzer: Provides audio feedback when an item is added to the cart.
6. Wires & Breadboard: Connect components.

**How It Works**
1. The RFID reader reads the tag attached to the item.
2. The system matches the tag with a predefined list of items (stored in the Arduino's memory).
3. If the item is found:
      The item's name and price are displayed on the LCD.
      The total bill is updated and displayed.
      The green LED lights up, and the buzzer sounds to confirm the item is added.
4. If the item is not found, the red LED lights up, and a message is displayed on the LCD indicating the item is not in the cart.

**Future Improvements**
1. Add a feature to remove items from the cart.
2. Connect to a database to dynamically update item prices and stock.
3. Implement wireless communication for a more sophisticated cart tracking system.

![image](https://github.com/user-attachments/assets/d9538e52-debb-4b67-8cc9-12d878c5053d)



https://github.com/user-attachments/assets/155b7851-01de-4d93-89c7-8ca70fa78e13


