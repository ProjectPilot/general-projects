# Authentication

## Level 0
* Create a web page that accepts 2 string values: username and password
* Create the backend that has an API that accepts username and password and returns true
* When the response is back from backend, forward the page to a simple page that say Hi **username**

Note: password should not be shown in plain text


## Level 1
* Add database to your application with a table that has 2 columns: username and password
* Add "user1" as username and encrypt your preferred password using https://emn178.github.io/online-tools/sha256.html and save these values to the database
* Change the backend so that when the API receives username and password
  * it encrypts the password (using any library you prefer)
  * Loads the user from database based on the username
  * compares the encrypted passwords and if they match, returns true. Otherwise return false
* Change UI so that if the backend returns false, stay on the page and show an error message: "Login failed"

## Level 2
Add Roles
* Define 3 roles in the database: Admin, Manager, User
* Change your application so that when the user logs in, based on the role they have they will see different messages. You can simply say: "Hi <user>! You are <role>"
* After the login,
 * Admin can see a link(dummy for now) to see all users and another link (dummy) to see website stats
 * Manager can a link to see all users and a link to see log in stats by users
 * User can only see their name and the message mentioned above.
