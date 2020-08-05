Based on: https://github.com/gSchool/herobook

Students will create a React app based on the technical descriptions below. Objectives:
- Practice TDD
- Practice mocking and DI
- Integration and unit testing.

The following specs don’t provide any details about implementation or use cases. Instead, it’s an abbreviated list of requirements that require you to discuss and plan each feature. Try to visualize the features based on their descriptions. Then write tests to develop an MVP (minimum viable product). 


## Tech Specs

### Navigation
* Home url
* Login/Logout url
* Favorites url

### Homepage 
* has navigation (routes)
* has search bar
* renders lists of clickable heroes

### Heroes
`{"id": "0", "Name": "A-Bomb", "Alignment": "good", "Gender": "Male", "EyeColor": "yellow", "Race": "Human", "HairColor": "No Hair", "Height": "203", "Weight": "441", “image”: “someurl.example.com” "powers": [ ]}`
* have unique page
* have stats displayed on their page
* Full CRUDL

### Search
* can search for heroes by name
* can view search results
* has filters for searching by powers and/or alignment

### Users
* can register
* can login/logout
* Full CRUDL
* can have a favorite heroes list
* can add/remove heroes on their list

## Stories

As a guest, I can browse a list of heroes by visiting the homepage.
* Given a guest, when they visit the homepage, they can see a list of heroes.

As a guest, I can search heroes by name from any page.
* Given a guest types search criteria into the search bar, when they press submit, it should display a list of heroes who match the criteria.

As a guest, I can create an account with my username and password.
* Given a guest clicks “Signup”, when they submit their username and password, then a new user is created.
* Given a login form, when a user provides the correct credentials, they’ll be redirected to the homepage.
* Given a login form, when a user provides incorrect login credentials, they’ll be redirected to the login page again and a message to “Try again” will be displayed.
* Given a user successfully logs in, when they’re redirected to the homepage, then the navigation should display a “Logout” button.
* Given a user clicks the “Logout” button, then they’ll be logged out and the navigation should display a “Login” button.

As a guest, I can click any hero on the heroes list to visit a page with more details.
* Given a list of heroes, when the hero is clicked, then it should display the Hero Details page.

As a user, I can add a new hero to the list of heroes.
* Given a user, when a valid New Hero Form is submitted, then the hero is added to the list of heroes.

As a user, I can create a list of my favorite heroes.
* Given a user, when the New List button is clicked, then it should display the New Favorites List form.
* Given a user has a favorites list, when they view the Hero List, they should see a heart button next to each hero on the list.

As a user, I can remove heroes from my favorites list.
* Given a favorites list, when a user clicks the heart button next to a hero, then that hero is added to that list.
* Given a user is viewing their favorites list, when they click the “Remove” button next to a hero, then the hero should be removed from the list.
