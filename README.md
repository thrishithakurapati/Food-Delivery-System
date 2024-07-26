# Food-Delivery-System
Project Description: Food Delivery System

The "Food Delivery System" is a command-line based application developed in Python. It simulates a basic food ordering and delivery experience similar to popular food delivery services like Swiggy or Uber Eats. This project aims to provide users with essential functionalities to browse restaurants, view menus, add items to a cart, place orders, and manage their orders effectively.

Key Features:

Restaurant Selection: Users can view a list of available restaurants participating in the system.

Menu Exploration: Upon selecting a restaurant, users can see a list of available items on the menu along with their prices.

Adding Items to Cart: Users can add multiple items from the menu of a selected restaurant to their cart.

Cart Management: Users can view the contents of their cart at any time, showing selected items and the total price.

Order Placement: Users can place their order, which confirms their selection and clears the cart for the next transaction.

Implementation Details:

Data Representation: Restaurants and their respective menus are represented using Python dictionaries. Each restaurant is a key in the main dictionary, and its value is another dictionary containing menu items as keys and their prices as values.

User Interaction: The application uses a command-line interface (CLI) to interact with users. It displays a menu of options and prompts users to enter choices using input functions.

Functionality: The core functionalities are implemented through various functions:

display_restaurants(): Lists all available restaurants.
display_menu(restaurant): Displays the menu of a selected restaurant.
add_to_cart(item, restaurant): Adds an item to the cart from the selected restaurant's menu.
display_cart(): Shows the current contents of the cart.
place_order(): Finalizes the order by confirming the items in the cart and clearing it.
Libraries Used: The tabulate library is utilized to neatly format and display menu items and cart contents in a tabular format within the command-line interface.

Usage:

Running the Application: Users execute the Python script (food_delivery_system.py) in a terminal or command prompt environment. They interact with the system by selecting options from the displayed menu to perform actions such as viewing restaurants, exploring menus, adding items to the cart, and placing orders.

Feedback and Confirmation: The system provides feedback at each step of the process, confirming actions such as adding items to the cart or placing an order. Error handling is incorporated to manage


The "Food Delivery System" in Python is a command-line application simulating restaurant menu browsing, item selection, cart management, and order placement. Users interact via a menu interface to view restaurants, add items to their cart, and finalize orders, providing a foundational understanding of basic Python programming and application development.

