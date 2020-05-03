# Burger
a burger logger with MySQL, Node, Express, Handlebars and a homemade ORM (yum!)

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