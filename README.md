# python-challenge-1  

  **Module 2 challenge**  
  Author: Yiannis Pagkalos. If you have any questions or feedback, feel free to contact me at yiannis.pagkalos@gmail.com.  
  
**Food Ordering System**:This is a Python-based food ordering system. It allows users to select menu items from various categories such as Snacks, Meals, Drinks, and Dessert, specify quantities, and then calculates the total cost of their order.

## Features  

- A multi-category menu including Snacks, Meals, Drinks, and Desserts.
- Continuous ordering process with a validation check on inputs.
- Adds ordered items to a list in dictionary format.
- Displays a receipt with itemized order details and a total cost calculation.  

## Menu Categories  

The menu is divided into the following categories:  

- Snacks: Items like cookies, bananas, apples, etc.
- Meals: Includes burritos, sushi, pizza, burgers, etc.
- Drinks: Various sodas, teas, and coffees.
- Desserts: Includes cakes, cheesecake, and other desserts.  


## How to Run  

1. Install Python: Make sure you have Python 3 installed on your system.  
2. Run the Script: Download the Python file and run it using the following command in your terminal or command prompt:
python menu.py  
3. Interaction: The program will display the menu, ask you to select items, and specify quantities. You can continue ordering multiple items until you choose to stop.  
4. Receipt Generation: Once you’ve completed your order, the program will display a detailed receipt, showing the items you ordered, their quantities, prices, and the total cost.  


## Order Flow  

- The system first displays the menu to the customer.
- The customer can select a category and pick an item from that category.
- Input validation ensures that only valid menu numbers and quantities are accepted.
- The customer’s selections are stored in the order_list, with each order item represented as a dictionary containing the Item name, Price, and Quantity.


## Example Interaction  

	Welcome to the variety food truck.
	Which menu would you like to order from? 
 
	  1: Snacks
	  2: Meals
	  3: Drinks
	  4: Dessert
 
	Type menu number: 2
	You selected Meals
	What Meal(s) item would you like to order?
	Item # | Item name                | Price
	-------|--------------------------|-------
	1      | Burrito                   | $4.49
	2      | Teriyaki Chicken          | $9.99
	3      | Sushi                     | $7.49
	4      | Pad Thai                  | $6.99
	5      | Pizza - Cheese            | $8.99
	6      | Pizza - Pepperoni         | $10.99
	7      | Pizza - Vegetarian        | $9.99
	8      | Burger - Chicken          | $7.49
	9      | Burger - Beef             | $8.49

 
	Please type the number of the item you wish to order: 1
	• How many Burritos would you like to order? (note: quantity will default to 1 if you enter an invalid input): 2
	• Would you like to keep ordering? (Y)es or (N)o: n
	• Thank you for your order.

	*This Is what we are preparing for you:*
	
	Item name                 | Price  | Quantity
	--------------------------|--------|----------
	Burrito                   | $4.49  | 2

	Total Price: $8.98


## Key Features  

1. Continuous Ordering: The customer can order multiple items from different categories in a single session.  
2. Input Validation: The program checks that the user input is valid for both menu item selection and quantity.  
3. Receipt: After the order is completed, the receipt is displayed with each item, its price, and the total amount due.  


