# E-Commerce-Back-End-ORM-DS-Mod13

E-Commerce Back End ORM DS-Mod13

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

This project is a back-end for an e-commerce site. It uses Express.js API and Sequelize to interact with a MySQL database. I had to configure a working API to use Sequelize to interact with a MySQL database. I utilized the dotenv package to use environment variables to store sensitive data, like my MySQL username, password, and database name. I also had to create database models using Sequelize and model associations to create relationships between them. I had to execute association methods on my Sequelize models to create the following relationships between them:
- Product belongs to Category.
- Category has many Product models.
- Product belongs to many Tag models. 
- Tag belongs to many Product models.
I allowed products to have multiple tags and tags to have many products by using the ProductTag through model.


Link: https://drive.google.com/file/d/1oVUGQFaxG_nBLCPZY8oQo4H576mJ0y6l/view?usp=sharing

Github Repo: https://github.com/Devarasen/E-Commerce-Back-End-ORM-DS-Mod13#usage

![Screenshot](./assets/Project%20Screenshot.PNG)

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation

Dependencies should be installed for code to run properly.

Run `npm install` to install dependencies as specified in package.json for application to run as intended.


## Usage

Instructions to run the application:

1.  Clone the repository to your local machine.
2.  Open the terminal and navigate to the root directory of the project.
3.  Run `npm install` to install the dependencies.
4.  Create a `.env` file in the root directory of the project. You can refer to `.env.EXAMPLE` as a guide.
5.  Add the following to the `.env` file , replacing the values with your own:

DB_NAME='ecommerce_db'  
DB_USER='root'  
DB_PW='password'  

6. Run `mysql -u - root -p` to open the MySQL shell.
7. Run `source db/schema.sql` to create the database.
8. Run `npm run seed` to seed the database.
9. Run `npm start` to start the server.
10. Open Insomnia to test the routes.



## Credits

Special thanks to all my tutors.

## License

MIT License

