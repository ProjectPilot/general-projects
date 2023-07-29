# Shopping Website

## Level 0
* Create a website UI that has:
  * A home page that show a list of 10 random items
  * Has a search bar to search based on category and price
  * Has a logo bar
  * Has a login/signup/profile area (you don't need to implement this feature for level 0)
  * Has a foot bar with "contact us" and "Terms of Service" information
 
* Create the backend that connects to database and has these APIs:
  * load a list of items based on a search query that returns 10 results. The search query can be empty which mean ALL items should be loaded

## Level 1
* Add paging to both UI and backend. The API should now also get a page number and include that in the search result.

## Level 2
* Add Sign up/Sign in using OAuth0
* Add a user Profile page to both UI and backend. Show user's picture, date of joining, Address and Phone

Note: Make sure each user can only see their own profile and no one is able to update someone else's profile

## Level 3
* Add Shopping cart
  * User should be able to select an item and add that item to their cart
  * User should be able to see everything in their cart and remove each item or increase/decrease the number of each item in the cart
  * User should be able to Checkout (for now, when the user clicks on Checkout, we think it's all paid and shipped. Just add the items to the user's purchased history list and save the shopping cart in the database)

## Level 4
* Add Shopping history to both UI and backend. Each item should have a unique order number with everything in the cart at the time of the checkout
