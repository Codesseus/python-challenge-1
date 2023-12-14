# Python-Challenge-1: Resturant Menu

## Overview:
This program recreates the funtunality of a resturant automated menu. It asks the user to choose a series of food items from a list and then prints out their order along with the total cost.

## Usage
1. After launching the program asks the user to input which menu they want to order from prompting them to enter a number that corresponds to a certain menu category such as 1 for snacks or 2 for meals. The program checks for invalid inputs and prompts the user to reenter a valid number if they failed to do so.

2. The program then dispalys the selected menu (both the foods and their unit costs) and asks the user to select an item from that menu by again prompting them to enter a number that corresponds to a menu item. The program checks for invalid inputs and prompts the user to reenter a valid number if they failed to do so.

3. The program then asks the user to input how many of the selected item that they want. The program checks for invalid inputs and prompts the user to reenter a valid number if they failed to do so.

4. After selecting the quantity of the item the programs asks the user iff they would like to keep ordering. If the user says yes then we repeat steps 1-4, otherwise the program moves on to order finialization. During this step the program checks to make sure that the user inputs either y or n, and it will propmt the user to input a valid response if they fail to do so.

5. During order finalization the program displays which food items the user selected, their unit price, and the quantity of that item the user selected in a table, and then it prints out the total cost of the order by summing the unit price of each item multiplied by how many of each item was ordered.

6. Finally the program  prints a goodbye message to the user and exits.