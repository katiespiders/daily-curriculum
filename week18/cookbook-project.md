# Cookbook

In this project, we will be building an AngularJS application with an Express 
and Node.js backend data source. The application will focus on building a 
multi-model recipe aggregation site, first focusing on building the back-end 
data source and then building an interactive front-end UI.

We will utilize many of AngularJS's unique features, focusing on creating
and gaining an understanding of how AngularJS handles routing, controllers, 
models, templates, and user interaction features like ng-click, ng-model,
and filters.

Students will work on individual applications, but they will be in a "co-worker" 
pair each day to communicate about problems, techniques, and progress. Students 
are encouraged to pair program or "mob" any issues or tasks that are difficult 
or confusing.

Students will also provide feedback each day on their confidence and comprehension 
of the material. This will help guide further development of their curriculum 
and help ensure that they get the review they need on particular parts of the 
frameworks.

## Goals

- Rapid Learning
- Learn the benefits of frameworks
- Build a Node.js database and a simple Express application
- Build an AngularJS application
- Further explore the area of frameworks that you find most interesting

**Stretch Goals**
- Create a custom directive


## Bronze

- Recipes include at least a:
    - Name
    - Description
    - String/text of ingredients
    - String/text of directions
- Recipes can be viewed as a list
    - This list can be filtered by a key word on the front-end
- Recipes can be viewed individually
- New recipes can be created
    - These recipes are saved to the database
- All data goes through the Express/Node.js data source
- App uses at least 1 of each of the following: ng-click, ng-if, ng-each, ng-model

## For Silver, Gold, and Platinum:
Choose from the following, based on your interests. 5 items from this list is 
silver. 5 more items (total of 10 additional items) is Gold. 5 more items 
(total of 15) is Platinum. All of the items is Super-Double-Plus Platinum.

The lists are written in order of approximate difficulty. DO start at the top
of the lists that interest you; DO NOT grab items randomly from the middle/bottom.

### Front-End/Angular Track
- 
- Create a custom directive

### Back-End Track


<!-- Old stuff past this point -->

## Silver

### Admin

- Checkout
    - Use a credit card processor to process and charge the given credit card
    - Record the credit card processor response as a transaction

- As an admin
    - I can see a map showing a pin for each order
    - I can see the total number of orders by country
    - I can refund a partial or full amount of the users order
    - I can manage/upload images for products from file
    
## Gold

- Add to Order
    - Address

- Cart
    - The customer can see additional Tax (9.5% if in WA state otherwise 0%)
    - The customer can enter basic shipping info to see shipping rates.
    - The customer can select a shipping rate (the total should update)

- As an admin
    - I can create a shipment with the correct carrier
    - When an order is marked as shipped
        - A shipping confirmation is sent to the customer
    - I can send an email including tracking information from the carrier

## Platinum

- As a customer
    - I can click a link to "Chat with Customer Service"
    
- As an admin, when a customer clicks to chat, if I am on the site:
    - A chat window opens, with a individual live dialog with each customer.
    