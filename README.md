# food_ordering

**Problem Statement**

You need to build a food ordering system. There are going to be multiple restaurants.
Example:
1. Truffles
2. Pasta Street
3. Punjabi House
4. Sultan Spice

Each of these restaurants will have specific set of menu. The items on menu of different restaurant can match.
Example:
1. Truffles Menu:
    * Bianca Pasta [400]
    * Garlic Bread [200]
    * etc...

2. Pasta Street:
    * Bianca Pasta   [550]
    * Garlic Bread   [250]
    * etc...
    
3. Punjabi House
    * Butter Chicken [450]
    * Naan           [50]

4. Sultan Spice
    * Butter Chicken [600]
    * Naan [100]
    * etc..

Now there are two use case:
1. A user can either search for specific restaurant and order from it's menu.
2. If the user searches for item, you need to display all items based on price sorted in descending order.

A user at a time can only place order from a restaurant. 
Each of these restaurant has processing power *P*. At any given point of time, any restaurant can run with processing power *(P<=N)*.
After each order is processed, processing power is restored of restaurant.

**Acceptance Criteria:**
1. Select item and add to cart.
2. Place order.
    a. After placing order, processing power should get deducted.
3. Should be able to check updated processing power of restaurant.
4. Should be able to mark an item completed for an order.
5. Repeat: 2(a)
6. Delete item from cart.