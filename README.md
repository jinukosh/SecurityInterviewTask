## About the Web App

This is a simple nodeJS web app with a list of all users with user authentication, user creation without duplicates, data modification, session persistent etc. The app is developed in node.js and express and connected to NoSQL database MongoDB. 

The directories of the app are
* [/public](./public) - static directories such as /images, currently including js which includes all the client interactions and css files
* [/routes](./public) - route files which implements the APIs and routes
* [/views](./views) - views powered by jade template engine
* [README.md](README.md) - this file
* [app.js](app.js) - central app file 
* [package.json](package.json) - package info

#### Run

Install mongodb in local machine

Start local mongoDB in cmd with command, for example,  `mongod --dbpath ~/Documents/mongo/db`.

To run the code, git clone and first run `npm install` to install all all required dependencies. Then, run `npm run live` to run the node server with nodemon and go to 'http://localhost:3000' for user interface and 'http://localhost:3000/admin' for admin interface.