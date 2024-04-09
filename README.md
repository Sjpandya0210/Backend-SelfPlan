# Backend-SelfPlan
    Project Management Requirements
1. GitHub Project
-Have detailed planning tickets with task descriptions for each one.
-Have a GitHub repository containing all relevant code for the project.

2. Functionality Requirements
Routes via Express Router  
/books - this could be the home page; this component should show all books in the library’s catalog
/books/:id  - this component should display details of an individual book
/login and /register (This could alternatively be displayed in the profile instead of living in its own route.)
/account  - this component should show, at minimum:
Username or email of logged in user
List of all books a user has checked out (or a message indicating they have 0 books checked out if applicable)

MVP

3. Unauthenticated Users should be able to:
Sign up for an account with a username and password.
Sign in with the correct username/password combination.

4. Authenticated Users should be able to:
 a. Check out an available book
 b. Return books they have currently checked out
 c. View their own account page and currently checked out books

5. Authenticated Users should not be able to:
 a.View the accounts of users other than themselves
 b.Checkout / Return books for other users
 c.View a list of all the library's books
 d.View details of an individual book      