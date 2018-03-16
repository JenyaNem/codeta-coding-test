# Codeta developer test
## Brief
As a user I want to see the games offered by the application.
As a user I want to register an account by completing a two step registration form and be able to login to the site to filter the games on country code.
## Conditions
Use the provided clean base from create-react-app (https://github.com/facebook/create-react-app) at https://github.com/opture/codeta-coding-test.git
(Regular npm scripts are unchanged from create-react-app)
The list of games shall provide a name and image to the user when not logged in, when the user is logged in, the user shall be able to filter the games on ISO country code. 
Stub data for games is provided as an export "Games" from games.js
Use property “name” for the game name, “thumbnail” for the image and filter games on property “restrictedTerritories”.
Login credentials can be hardcoded, and does not have to be related to a successful registration.
The registration shall be splitted into two steps, and a third step that shows a confirmation of registration. The user shall be able to switch between the first and the second step.
There is no backend supplied, either simulate the calls in javascript, use a local store of any choice or use a backend of your choice, but make sure it is publicly available.
There is no set design for the task, the design is not evaluated, the layout has to be considered usable though.
## Requirements
Registration step 1. shall contain the following information:
Username, password, email address, phone number.
Registration step 2. shall contain the following
Firstname, lastname, birthdate, ability for the user to either accept or decline a newsletter from the site.
Registration step 3 shall display a confirmation message if the registration was successful. 
Login shall contain fields, username and password.

The UI shall be implemented in React, use create-react-app for simplicity, apart from that you are free to add any libraries and frameworks you feel appropriate. It should be implemented as a single page app, page reloads are not allowed.
Delivery
Publish your solution to a public github repository and send the link to ph.westman@codeta.com. Provide a short description of your solution and any information that is needed to run the application.  
