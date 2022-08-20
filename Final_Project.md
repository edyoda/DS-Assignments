# You have to design a Food Ordering app for a restaurant

## The application will have a log-in for admin and users to log-in

--------------------- Admin ----------------------------------

:arrow_right: Admin will have the following functionalities:

    1. :point_right: Add new food items. Food Item will have the following details:

        - FoodID //It should be generated automatically by the application.
        - Name
        - Quantity. For eg, 100ml, 250gm, 4pieces etc
        - Price
        - Discount
        - Stock. Amount left in stock in the restaurant.

    2. :point_right: Edit food items using FoodID.

    3. :point_right: View the list of all food items.

    4. :point_right: Remove a food item from the menu using FoodID.

--------------------- User ----------------------------------

:arrow_right: The user will have the following functionalities:

    1.:point_right: Register on the application. Following to be entered for registration:

        - Full Name
        - Phone Number
        - Email
        - Address
        - Password

    2. :point_right: Log in to the application

    3. :point_right: The user will see 3 options:
        - Place New Order
        - Order History
        - Update Profile

    4. :point_right: Place New Order: The user can place a new order at the restaurant.
        - Show list of food. The list item should as follows:
            - Tandoori Chicken (4 pieces) [INR 240]
            - Vegan Burger (1 Piece) [INR 320]
            - Truffle Cake (500gm) [INR 900]
    
    5. :point_right: Users should be able to select food by entering an array of numbers. For example, if the user wants to order Vegan Burger and Truffle Cake they should enter [2, 3]

    6. :point_right: Once the items are selected user should see the list of all the items selected. The user will also get an option to place an order.

    7. :point_right: Order History should show a list of all the previous orders

    8. :point_right: Update Profile: the user should be able to update their profile.

----------------------------------------------------------------------

## Upload the python files on Github and submit the Github repo URL on the assignment page
