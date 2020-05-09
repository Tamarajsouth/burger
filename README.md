# Burger
a burger logger with MySQL, Node, Express, Handlebars and a homemade ORM (yum!)

## Eat-Da-Burger! 
* a restaurant app that lets users input the names of burgers they'd like to eat.

* Whenever a user submits a burger's name, the app will display the burger -- waiting to be devoured.

* Each burger in the waiting area also has a `Devour it!` button. When the user clicks it, the burger will move to the bottom of the page under the `Devoured` menu.

* The app stores every burger in a database, whether devoured or not.

## UI

![burgimg](https://i.ibb.co/gvZznFq/Screen-Shot-2020-05-09-at-10-04-26-AM.png)

## Utilities Used
1. Node.js
2. Express
3. Express Handlebars npm package
6. MySQL npm package

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
│       │   └── style.css
│       └── js
│           └── burgers.js
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