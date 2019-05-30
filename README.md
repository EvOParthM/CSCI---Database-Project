# CSCI---Database-Project
CSCI Database Project with the ability to add items and create contracts with the use of SQL

Steps to run/edit the program
•	To edit this project, you will need to download Eclipse IDE from https://www.eclipse.org/ide/
•	Download the program through a GitHub repository/preferred through our USB drives and run the ContractSuppliesSystem.jar file.
•	To view the database and manage it, open the contract_supplies_database.db in SQLite studio. 

Explanation for each window
1)  Enter New Supplier
In this window you can enter the Supplier Name, Street Address, City, State and Zip code to a new supplier that will be saved onto the database when you click “Enter Supplier.” The user has an option to return to home if they wish to go back to the homepage. 

2)	Enter Item
This window lets the user enter a new item with a Name and Item Description that is 20 characters long. The item will be saved onto the database when the user clicks on “Enter Item.” The user has an option to return to home if they wish to go back to the homepage. 

3)	Create New Project
In this window the user can state the project that they will be working on and write the information related to it. The project data is 256 characters long and it saves onto the database when the user clicks on “Create Project.” The user has an option to return to home if they wish to go back to the homepage.

4)	Create New Contract
You can choose an existing supplier and item from the database and add a quantity and price per Item. This window lets you add multiple different items in a contract, but it gives an error if the user is placing the same item in a contract twice. Once you click on “Enter Item” it should preview the information on a window next to it. Finally, the user can either restart the contract by clicking on “Restart Contract” or create the contract with the items and supplier by clicking on “Create Contract.” The user has an option to return to home if they wish to go back to the homepage.
  
5)	Place Order
Placing a new order requires the date you want the order to arrive by, the project that this order is geared towards, the contract that you want to pick from, the item that you are ordering and the quantity that you’re ordering. When the user clicks on “Enter Item” it generates a preview in the order preview window. Finally, the user can either restart the order by clicking on “Restart Order” or create the order with the items and supplier by clicking on “Place Order.” The user has an option to return to home if they wish to go back to the homepage.

6)	Find Items in an Order
You can find the items in an order by picking the order id and when you click on “Find items” it should generate a list of items that were in the order. The user has an option to return to home if they wish to go back to the homepage.
 
7)	Find Item Price by Order
In this window you can pick an order and the items in that order to determine the price of that item when the user clicks on “Find Price.” The user has an option to return to home if they wish to go back to the homepage.
 
8)	Find Orders by Item
This window lets the user pick an item and see the date that the item was placed for and the price that this item was placed at. The user has an option to return to home if they wish to go back to the homepage.
 
9)	Find Item Price by Contract
Just like with finding an item price by order, finding item price by contract allows the user to pick a contract and an item to find the price for one of the items when they click on “Find Price.” The user has an option to return to home if they wish to go back to the homepage.
 
10)	 Find Contracts by Supplier
This window allows the user to find the contract that was created by selecting a specific supplier and the date the contract was created when the user clicks on “Find Contract.” The user has an option to return to home if they wish to go back to the homepage.
 
11)	 Find Item Quantity
The user can pick a contract and an item in that contract to view the quantity of that item in that contract when the user clicks on “Find Quantity.” The user has an option to return to home if they wish to go back to the homepage.
 
12)	 Generate Report
When the user clicks on “Generate Report,” a window shows the contract id, item id and the order quantity for that contract in a list. The user has an option to return to home if they wish to go back to the homepage.
 
13)	 Exit
Upon clicking the “Exit” button, the window closes, and it ends the program.
