# osullivan-challenge-thirteen-e-commerce

## User Story
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies

## Acceptance Criteria
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database

## Description

Students are tasked with building the back end for an e-commerce site using a working Express.js API and configuring it to use Sequelize to interact with a MySQL database.

## Installation

Run npm install and the necessary modules will be installed from package.json. Log in to mysql and create the database using schema.sql. Then seed the database with starter ecommerce information by using 'node run seed'. Run npm start to run the server.js file in the CLI. Use Insonia to verify post, put, and delete request functionality for products, categories, and tags.

## Usage

This ecommerce database can be used to view, update, add, or delete products, product categories, or product tags.

Video Walkthrough - (https://drive.google.com/file/d/1AANtLix8ojuKbEnQDwEVxko_J3HVqXwT/view)

## Credits

Used Node.js (https://nodejs.org/en) and MYSQL (https://www.mysql.com/). Used node packages Inquirer (https://www.npmjs.com/package/inquirer), Express (https://www.npmjs.com/package/express),  mysql2 (https://www.npmjs.com/package/mysql2), Sequelize (https://sequelize.org/), and dotenv (https://www.npmjs.com/package/dotenv). Seed data provided by UC Berkeley. All code written by Michael O'Sullivan.

## License

MIT License

![Model](https://github.com/michaelhallosullivan/osullivan-challenge-thirteen-e-commerce/blob/main/examples/ecommerce-products.jpg)