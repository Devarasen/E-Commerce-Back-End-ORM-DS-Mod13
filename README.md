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


Link: https://drive.google.com/file/d/1JhoCIY9MZ27SQSBAQ5L_h5LlovLavWyL/view?usp=sharing

Github Repo: https://github.com/Devarasen/Employee-Tracker---SQL

![Screenshot](./assets/Project%20Screenshot.PNG)

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation

Dependencies should be installed for code to run properly.

Dependencies used are: - inquirer: v8.2.4 - console.table: ^0.10.0 - dotenv": ^16.3.1 - mysql2": ^2.2.5

Project tested on node v16.20.1

## Usage

Instructions to run the application:

1.  Clone the repository to your local machine.
2.  Open the terminal and navigate to the root directory of the project.
3.  Run `npm install` to install the dependencies.
4.  Create a `.env`.env file in the root directory of the project.
5.  Add the following to the `.env`.env file , replacing the values with your own:


## Credits

Special thanks to all my tutors.

## License

MIT License

