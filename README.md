# Burger
a burger logger with MySQL, Node, Express, Handlebars and a homemade ORM (yum!)

## Eat-Da-Burger! 
* a restaurant app that lets users input the names of burgers they'd like to eat.

* Whenever a user submits a burger's name, the app will display the burger -- waiting to be devoured.

* Each burger in the waiting area also has a `Devour it!` button. When the user clicks it, the burger will move to the bottom of the page under the `Devoured` menu.

* The app stores every burger in a database, whether devoured or not.

## App Setup
1. Github Repo called `burger`
2. make a package.json file by running `npm init` 
3. install Express npm package `npm i express`
4. create a `server.js` file
5. install Handlebars npm package `npm i express-handlebars`
6. install MySQL npm package `npm i mysql`
7. require express npm package inside server.js file

## Directory Structure

```
.
├── config
│   ├── connection.js
│   └── orm.js
│ 
├── controllers
│   └── burgers_controller.js
│
├── db
│   ├── schema.sql
│   └── seeds.sql
│
├── models
│   └── burger.js
│ 
├── node_modules
│ 
├── package.json
│
├── public
│   └── assets
│       ├── css
│       │   └── burger_style.css
│       └── img
│           └── burger.png
│   
│
├── server.js
│
└── views
    ├── index.handlebars
    └── layouts
        └── main.handlebars
```

## Submission Requirements 

* **This assignment must be deployed.** 
* Submit both the deployed Heroku link to the homework AND the link to the Github Repository!