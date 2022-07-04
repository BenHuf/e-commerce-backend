# E-commerce Back End

## Demonstration
Video demonstration of the program is provided [here](https://drive.google.com/file/d/1MGp5WxxBDqWGBOqmJ4QGp1ufL6Cim2SC/view?usp=sharing)

## Purpose
To handle requests and reponses from the front end of an ecommerce website. This includes GET, POST, PUT, and DELETE routes for categories, products, and tags in a database.

## Built With
* Javascript
* Express.js
* MySQL
* MySQL2
* Dotenv
* Sequelize

## Installation
To install, clone the repository at the link below and run the following commands in the root of the directory.

* `npm init -y`
* `npm i express mysql2 dotenv sequelize`

## Usage
To use this program:

* Create a .env file at the root of the directory containing the following (where DB_PW is your MySQL password)
    * DB_NAME='ecommerce_db'
    * DB_USER='root'
    * DB_PW=''

* Create the database by running `mysql -u root -p`, entering your password, and running the command mysql> `source db/schema.sql`. You can then quit mysql by running the command mysql> `quit`

* Run `npm run seed` to seed the newly created databse

* Lastly run `npm start` to run the server

## GitHub Page Link
[https://github.com/BenHuf/e-commerce-backend](https://github.com/BenHuf/e-commerce-backend)

## Contribution
BenHuf (Benjamin Huffman) [https://github.com/BenHuf](https://github.com/BenHuf)