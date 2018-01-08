# burger

Overview

A Node, Express, Handlebars, and MySQL burger appthat lets users input the names of burgers that they'd like to eat and then devour them. 

Here is the Launched app on Heroku
https://warm-scrubland-83338.herokuapp.com/

Demo Vedio link
https://drive.google.com/file/d/1XqUJyV35CsTn1BEYD0v0vN2KdRyQyhBy/view?usp=sharing

Directory Structure:

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
		│   ├── assets
		│   │   ├── css
		│   │   │   └── burger_style.css
		│   │   └── img
		│   │       └── burger.png
		│   └── test.html
		│
		├── server.js
		│
		└── views
		    ├── index.handlebars
		    └── layouts
		        └── main.handlebars

INSTALLATION

To run the application locally, first clone this repository with the following command.

	git clone git@github.com:nbnsireesha/burger.git

Next, install the application dependencies.

	cd burger
	npm install

Finally, run the node server locally.

	node server

Now, open the local application on port 300 at the URL:http://localhost:3000/