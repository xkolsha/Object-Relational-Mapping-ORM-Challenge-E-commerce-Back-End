# README.md for Object-Relational Mapping (ORM) Challenge: E-commerce Back End

## Table of Contents

1. [Description](#description)
2. [User Story](#user-story)
3. [Acceptance Criteria](#acceptance-criteria)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Features](#features)
7. [Mock-Up](#mock-up)
8. [Deployment](#deployment)
9. [Associations](#associations)
10. [NPM Scripts](#npm-scripts)
11. [Credits](#credits)
12. [License](#license)
13. [Badges](#badges)

## Description

The purpose of this challenge is to build the back-end logic for an e-commerce platform using Express.js, Sequelize, and MySQL. The project aims to deliver a robust API for e-commerce applications, allowing businesses to be more competitive in the digital marketplace.

## User Story

- **AS A** manager at an internet retail company
- **I WANT** a back end for my e-commerce website that employs the latest technologies
- **SO THAT** my company can vie effectively with other e-commerce businesses

## Acceptance Criteria

- **GIVEN** a functional Express.js API
- **WHEN I** input my database name, MySQL username, and MySQL password into an environment variable file
- **THEN I** can connect to a database using Sequelize
- **WHEN I** execute schema and seed commands
- **THEN** a development database is initialized and populated with test data
- **WHEN I** run the command to start the application
- **THEN** my server starts and the Sequelize models synchronize with the MySQL database
- **WHEN I** test API routes for categories, products, or tags in Insomnia Core
- **THEN** the data for each route is displayed in formatted JSON
- **WHEN I** try out API POST, PUT, and DELETE operations in Insomnia Core
- **THEN I** can successfully create, update, and remove data in my database

## Installation

1. Clone the repository: `git clone https://github.com/xkolsha/Object-Relational-Mapping-ORM-Challenge-E-commerce-Back-End`.
2. Install dependencies: `npm install`.
3. Create a `.env` file in the root of the project and update it with your MySQL user and password.
4. Create a database using MySQL shell commands: `mysql -u root -p` and `source db/schema.sql`.
5. Set up MySQL database and update `.env` with your MySQL user and password.

## Usage

Run `npm start` to start the application. Use Postman/Insomnia Core for testing the API endpoints.

## Features

- CRUD functionalities for categories, products, and tags.
- Sequelize ORM for easier database operations.
- Environment variables for database configurations.

## Mock-Up

To view the video mock-up, click [HERE](https://1drv.ms/u/s!As0hKguCANy1u40J9Wo6n-FSegXDXQ?e=jDOAYg).

![Mock-up of the website](/public/images/Screenshot%202023-09-16%20172256.png)
![Mock-up of the website](/public/images/Screenshot%202023-09-16%20172224.png)

## Deployment

- **GitHub Repo**: [Object-Relational-Mapping-ORM-E-commerce-Back-End Repository](https://github.com/xkolsha/Object-Relational-Mapping-ORM-Challenge-E-commerce-Back-End)

## Associations

- `Product` belongs to `Category`
- `Category` has many `Product` models
- `Product` has many `Tag` models
- `Tag` has many `Product` models

## NPM Scripts

- `npm start`: Starts the application
- `npm run watch`: Starts the application using nodemon for development
- `npm run seed`: Seeds the database

## Credits

- [Node.js](https://www.npmjs.com/package/node)
- [Express.js](https://www.npmjs.com/package/express)
- [MySQL](https://www.npmjs.com/package/mysql)
- [Sequelize](https://www.npmjs.com/package/sequelize)
- [Postman](https://www.postman.com/)
- [dotenv](https://www.npmjs.com/package/dotenv)
- [W3Schools - Node.js Tutorial](https://www.w3schools.com/nodejs/)
- [W3Schools - Express.js Tutorial](https://www.w3schools.com/nodejs/nodejs_express.asp)
- [W3Schools - SQL Tutorial](https://www.w3schools.com/sql/)
- [MDN - JavaScript Guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide)
- [MDN - Express Web Framework (Node.js/JavaScript)](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs)
- [Postman Learning Center](https://learning.postman.com/)

## License

MIT License

Copyright (c) 2023 [`Aviad Kohn`](https://github.com/xkolsha)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Badges

![badmath](https://img.shields.io/github/license/xkolsha/unbModule1Challenge?color=%238F83ED)
