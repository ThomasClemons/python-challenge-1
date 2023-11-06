# python-challenge-1
Assignment for AI/ML Bootcamp Module 2 Challenge
# Order System

This is a class assignment to create an ordering system that allows customers to place an order, store the customer's order, and print the receipt with the total price of all items ordered.
---------------------------------------------------------------------

## Description

The class was given starter code that creates the menu, captures customer input, and prints menu.  Our assignment was to adapt this starter code into a complete program that that allows customers to place an order, store the customer's order, and print the receipt with the total price of all items ordered.

## Getting Started

### Dependencies

- Python 3.6 or higher

### Installing

- Clone this repo to your environment

### Executing program

- Run program '**menu.py**' from your cloned repo folder in using terminal
- This program will loop until (N)o is entered.  Follow the prompts to select items from the menu.

While loop until (N)o is entered:

1. Menu categories are displayed on screen
<pre>From which menu would you like to order?
1: Snacks
2: Meals
3: Drinks
4: Dessert
</pre>

2. Enter a number corresponding to the item you would like to order at the "**Type menu number:**" prompt

**Example selecting menu item 1, Snacks:**

<pre>Type menu number: 1
</pre>

3. After your entry, a submenu for the selected menu item will be displayed:

**Example submenu for item 1, Snacks:**

<pre>What Snacks item would you like to order?
Item # | Item name                | Price
-------|--------------------------|-------
 1     | Cookie                   | $0.99
 2     | Banana                   | $0.69
 3     | Apple                    | $0.49
 4     | Granola bar              | $1.99
</pre>

4. Enter the number corresponding to the item you would like to order at the "**Please enter the item number you would like to order:**" prompt.

**Example selecting menu item 1, Cookie:**

<pre>Please enter the item number you would like to order: 1
</pre>

5. Enter the quantity of the item you would like to order at the "**You selected 'Menu Item', How many would you like to order?**" prompt.

**Example entering quantity of 1 for menu item 1, Cookie:**

<pre>You selected 'Cookie', How many would you like to order? 1
</pre>

6. Enter 'Y(es)' to continue or 'N(o)' to stop ordering at the "**Would you like to keep ordering? (Y)es or (N)o** prompt

<pre>Would you like to keep ordering? (Y)es or (N)o
</pre>

-  Enter 'Y(es)' to continue ordering items from the menu
-  Enter 'N(o)' to stop ordering

7. When 'N(o)' is entered, an Order Summary and Order Receipt will be displayed on the terminal and the program ends.

**Order Summary Example:**

<pre> 
Item name                 | Price  | Quantity
--------------------------|--------|----------
Cookie                    | $0.99  | 1
Tea - Thai iced           | $3.99  | 2
Fried banana              | $4.49  | 3
</pre>

**Final Receipt Example:**

<pre>Your Order is ready for pickup.

Variety Food Truck - Customer Order Receipt

Item name                 | Price   | Quantity | Item Total
--------------------------|---------|----------|-----------
Cookie                    | $ 0.99  |      1   | $   0.99
Tea - Thai iced           | $ 3.99  |      2   | $   7.98
Fried banana              | $ 4.49  |     10   | $  13.47
------------------------------------------------------------

                                   Total Price   $  22.44

------------------------------------------------------------

Thank You from Variety Food Truck.  Have an Awesome Day!
</pre>

## Help

- Error messages will be displayed for any invalid entries
- **Note:**  Quantity is defined as an integer, so you can enter very large quantities.  The program will work if a large quantity is entered, but the receipt format will be impacted if a quantity of 1000 or larger is entered.

## Authors

- Author:  Tom Clemons

## Version History

- 0.1
    - Initial Release

## Acknowledgments

- Inspiration, code snippets, etc.
  - [DomPizzie-Readme](https://gist.github.com/DomPizzie/7a5ff55ffa9081f2de27c315f5018afc)
