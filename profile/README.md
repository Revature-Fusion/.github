# Fusion Application

## Project Description

The Fusion Application is an e-commerce shopping application that is used by Guests, Users, and Admins. Just like within a store, Fusion holds multiple different products that one can view, add to their cart, and purchase. Outside of shopping functionality, there is the security of a login that Users and Admins will have to differenciate the actions that are available to them, as well as to seperate from a Guest. Logged-in Users will be able to complete the shopping functionalities as well as view their past orders that have already been completed under that account. Guests do not have to login to purchase anything, but do have an opiton to register for an account if they wish to view their completed purchases at a later time. Overall, this project was completed within a sprint of about two weeks with a team of 22 people developing and testing. Throughout the creation of Fusion, the primary focus was on Testing Automation along with the creation of a working e-commerce application.

## Technologies Used

* Postgres SQL through Amazon RDS
* Python - version 3
* Psycopg2
* PyTest
* Flask 
* Postman
* Java
* JDBC
* Junit
* Javelin
* Selenium and Cucumber
* JavaScript
* HTML
* CSS

## Features

* Users and Admins can log into the application
* Users can register a new account
* A User, Guest, or Admin can see a list of available products to add to their cart
* A User or Guest should be able to add/remove items from their cart
* A User or Guest should be able to checkout items from their cart
* Items that are checkouted by a User or Guest should remove them from the store inventory
* Users should be able to view their previous orders and the details of those orders

## Getting Started

Create 3 seperate local repositories using the following commands:
* git clone https://github.com/Revature-Fusion/Fusion-frontend.git
* git clone https://github.com/Revature-Fusion/Fusion-java.git
* git clone https://github.com/Revature-Fusion/Fusion-python.git

## Usage

There are 3 different repositories. One that holds the Frontend, one that holds the Java backend, and another that holds the Python backend.

1) Start the Postgres server and run the sql script. Enter your database details and put it in resources folder as connection.properties

2) Next within the Java Backend Local Repository, open the Fusion folder with IntelliJ and check the resource folder in /java/main to see if there is a connection.properties file. If there is not one, make one and input your database details within.

Then open up JDBC Connection under /java/main/util and run to test connection to the database, once connected to the database, run the App class within /java/main/app

3) Then within the Python Backend Local Repository, open the project in Pycharm and navigate to the dbconnection.py to set up your database connection within the /util folder.

Afterwards, open the app.py and run the file

4) Once both app files from Java and Python are running, open the index.html file in the Frontend Local Repository

5) Navigate throughout the site, and try out different features & interactions

## Contributors

* Courtney-Sage
* Blair Desjardins
* Faysal Adigun
* Vision Paudel
* Naomi Scott
* Tomi Solaja
* Sonu P.
* Patrick Castro
* Alexander Ottosson
* Kavitha Shashidharan
* Ezeniel Rios
* Bryan Yancey
* Gabriel Louis-Charles
* Jeremiah Lupton
* Izzi Salcedo
* Timothy Gottlieb
* Zane Rush
* Adrian M.
* Tolu Agboke
* Keith Smith
* David
* Seada Ebrahim

## License

Copyright (C) 2022 - Authors at Revature LLC. 

The {Fusion Application} project can not be copied and/or distributed without the express
permission of Revature
