# Phonebook

## Level 0
Create a web page for a phonebook application. This Web page can be written in any JavaScript framework. The entries are:

* First Name
* Last Name
* Phone Number
* Email
* Birth Date

** Apply validation on each field (use Regex whenever applicable):
*** Either first name or Last name has to be filled. If both are empty, show an error
*** Phone number can't be empty
*** Phone number has to be only numbers
*** Phone number has to be a valid phone number based on the country you live in (min/max length, replace first 00 with +)
*** Email has to be a valid email
*** Birth Date has to be a valid date

## Level 1
Create a backend for your application that:

* Has an API to receive the contact information


## Level 2
Add a database to your application and add the following APIs to your application:
* Save the contact
* Update the contact

Now, change the UI so that
* When the user loads the first page, it shows the "New Contact" page
* Add the Save button and when the user clicks the Save button, IF the inputs are valid, it calls the Save API
* Check IF the contact already exists. If it exists, update the contact else save the contact as a New contact


## Level 3
Add these APIs to your backend:

* Load ALL contacts
* Load the contact
* Search for a contact by partial name, or phone number

Change the UI so that:
* When user goes to the home page, it loads the list of all contacts (only show first name, last name and number) and
* Show a search bar with a Text box and Search button
* When user types a value in the search textbox and hits Search, call the Search API and show the result in the UI
* When user double clicks on the contact, open a popup, call Load contact API and show all the contact information in the popup page 







