Based on: https://github.com/gSchool/herobook

Students will create a React app based on the technical descriptions below. Objectives:
- Practice TDD
- Practice mocking and DI
- Integration and unit testing.

Tests will need to be written for more complex objects such as forms. 


## Tech Specs

### Homepage 
* has navigation (routes)
* has search bar
* renders lists of heroes

### Heroes
`{"id": "0", "Name": "A-Bomb", "Alignment": "good", "Gender": "Male", "EyeColor": "yellow", "Race": "Human", "HairColor": "No Hair", "Height": "203", "Weight": "441", “image”: “someurl.example.com”}`
* have unique page
* have stats displayed on their page
* can be updated

### Search
* can search for heroes by name
* can view search results
* has filters to search by: powers, species, and gender

### Users
* can register
* can login/logout
* can have a favorite heroes list
* can add/remove heroes on their list
