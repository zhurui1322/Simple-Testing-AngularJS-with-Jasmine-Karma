# Simple-Testing-AngularJS-with-Jasmine-Karma
simple testing AngularJS application by using Jasmine and Karma

Make sure you have NodeJs install in your computer 
## Setup

nvm use 5.0

npm install

node server.js

## Test

npm install -g karma-cli

karma start

### About this program
The simple angular application aims to use Jasmin and Karma to test all the javascript code are working properly.

This application displays several users' information such as: 
     id
     name
     role
     location
     twitter
     favorite Pokemon
     
once click the username, it will display an avatar of each user's favorite Pokémon on their individual profile page using Pokéapi API.


### Testing

There are 14 test case and all the test case passed

Test the controller and a service that hits a real API. In my service tests, I utilized $httpBackend to listen to HTTP endpoints and $q to resolve or reject our expected responses from the API. 
Test the controllers with all of its dependencies including the tested services. Given that the users can have valid or invalid favorite Pokémon names. Finally learned did test the logic within our controller. I did this using multiple controller instances within our tests each with their own resolvedUser.
