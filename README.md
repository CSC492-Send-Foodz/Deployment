# Introduction

A peer to peer food rescue platform to help grocery retailers donate to-be-discarded but edible produce to nearby food banks through a network of independently contracted drivers. 

### Brief Background
Across Canada, over 58% of all grocery produce is either wasted or lost annually. Translating to ~35.5 million tons of food, with a value of $49 billion, completely unused sitting in landfills across the country. Not only is this an alarming amount of waste which could be helping those who need it, but this waste is also leading to 56.6 million tonnes of carbon dioxide-equivalent emissions.

Many food banks are in constant search for additional produce donations, especially perishables, with  ⅙ people nationally using food banks as a means of support. However, food banks often cite the lack of efficient transportation means as a major deterrent due to limited resources. 

### The Vision
Send Foodz is meant to:
1. Efficiently rescue and redistribute excess food products to those in need.
2. Reduce carbon emissions from food waste at the retail level.
3. Provide fair compensation for drivers.

By creating a platform where grocery retailers can quickly upload an inventory of donated products to a web app for rescuing by nearby registered food banks. Once a food bank requests an order of the donated inventory, the drivers will be tasked for pick up and delivery, all while limiting the expenditure of any food retailer or food bank resources. 

# Products
### Web App - Food Bank
Users are able to:
1. Signup and log in with Firebase Authentication in order to access all features.
2. Check out each grocery retailer location registered with the platform.
3. Check out in real-time the available donation inventory for each location.
4. Add products from a single location to an order’s shopping cart. Products of 
different locations cannot be added to the same order. 
5. Be prompted, when adding a product from a secondary location, to either begin a
new order’s shopping cart or return to complete the current order before returning for this one. 
6. Select and edit the quantity of each product being added to the order.
7. View an order’s shopping cart and remove items.
8. Place an order and receive feedback around the order either.
9. Check out in real-time all currently active orders.
10. Confirm an order has been delivered. 

### Web App - Grocery Store
Users are able to:
1. Signup and log in with Firebase Authentication in order to access all features.
2. Donate an inventory of products by uploading a CSV file in the following format.
3. Check out in real-time the available donation inventory.
4. Remove products from the donation inventory.
5. Check out in real-time all currently active orders.
6. Confirm an order has been picked up.

### Mobile  App - Driver
Users are able to:
1. Signup and log in with Firebase Authentication in order to access all features.
2. Receive push notification notifying of a new potential order.  
3. Display all potential orders if not currently conducting a delivery. 
4. Accept & Decline a potential order. Cancel an ongoing delivery.
5. Display Map indicating the direction to the next checkpoint in the delivery process.
