# Restaurant Management System
This repository contains a restaurant management system implemented in Visual Basic .NET. The system comprises three forms: Form1, Form2, and Form3, each serving specific functions within the restaurant management workflow.

## Form1 - Table Management
### Functionality
* Displays the status of restaurant tables.
* Allows the user to assign waiters to tables.
* Provides visual feedback on table occupancy.
### Usage
1. Table Status Viewing:
* Upon opening the application, the user is presented with Form1, which displays the status of restaurant tables.
* Green color indicates an available table, while red indicates an occupied table.
2. Table Assignment:
* The user can assign a waiter to a table by selecting the table and choosing a waiter from the dropdown menu.

## Form2 - Order Placement
### Functionality
* Allows the user to select menu items for each table.
* Enables the user to customize orders based on customer preferences.
* Provides real-time updates on selected menu items.
### Usage
1. Menu Item Selection:
* After selecting a table on Form1, the user proceeds to Form2 to place an order.
* The user selects menu items from the available options and customizes the order as needed.
2. Real-time Updates:
* As the user selects menu items, Form2 provides real-time updates on the selected items, allowing the user to review the order before submission.

## Form3 - Order Payment
### Functionality
* Processes payments for orders.
* Updates the order status upon payment confirmation.
* Clears selected items from the order list.
### Usage
1. Payment Processing:
* After placing an order on Form2, the user proceeds to Form3 to process the payment.
* The total order value is displayed, and the user confirms the payment amount by clicking the "Cobrar" (Pay) button.
2. Order Status Update:
* Upon payment confirmation, Form3 updates the order status to reflect that the payment has been processed.
* The selected items are cleared from the order list, and the table status is updated accordingly.

## File Description
* Form1.vb: Contains the code for the Form1 table management form.
* Form2.vb: Contains the code for the Form2 order placement form.
* Form3.vb: Contains the code for the Form3 order payment form.
* Form1.Designer.vb, Form2.Designer.vb, Form3.Designer.vb: Automatically generated files containing the designer-generated code for the form layouts and controls.
