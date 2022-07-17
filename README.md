# ORM_E-commerce-Back-End

[![License: MIT](https://img.shields.io/github/license/tiffany-brand/professional-README-generator?style=plastic)](./LICENSE)

## Visual Presentation :

The below link is a demonstration of how this application works in the termianl and insomnia .

View a complete walkthrough video that demonstrates the functionality of the e-commerce back end: [E-commerce-Back-End](https://drive.google.com/file/d/1M_cLfTrsWvkfGJ2ZNzClNaH2fUm0D4oa/view)

## Table of Contents

- [Description](#description)
- [User Story](#userStory)
- [Acceptance Criteria](#acceptance-criteria)
- [Technologies](#technologies)
- [Usage](#usage)
- [Installation](#installation)
- [License](#license)
- [Questions](#questions)

## Description:

This project is the creation of the back end for an e-commerce site. This application used Express.js API and Sequelize to interact with a MySQL database. This application displays creation of database using mySQL with models and associations. Then demonstrates the API Routes to perform RESTful CRUD operations displayed in my walk through videos.
Built using MySQL2, Express, Sequelize and dotenv.

## User Story:

`AS A manager at an internet retail company I WANT a back end for my e-commerce website that uses the latest technologies SO THAT my company can compete with other e-commerce companies`

## Acceptance Criteria:

GIVEN a functional Express.js API

- WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
  - THEN I am able to connect to a database using Sequelize
- WHEN I enter schema and seed commands
  - THEN a development database is created and is seeded with test data
- WHEN I enter the command to invoke the application
  - THEN my server is started and the Sequelize models are synced to the MySQL database
- WHEN I open API GET routes in Insomnia for categories, products, or tags
  - THEN the data for each of these routes is displayed in a formatted JSON
- WHEN I test API POST, PUT, and DELETE routes in Insomnia
  - THEN I am able to successfully create, update, and delete data in my database

## Technologies:

<p>
 <img src="https://img.shields.io/badge/-MySQL2-red" />
<img src="https://img.shields.io/badge/-JavaScript-purple" />
<img src="https://img.shields.io/badge/-Sequalize-green" />
<img src="https://img.shields.io/badge/-express-grey" />
 <img src="https://img.shields.io/badge/-dotenv-red" />
 </p>

## Usage:

- To create the schema from the MySQL shell run the following in command line
  - `mysql -u root -p`
  - Enter PW when promted
  - `source db/schema.sql`
  - `quit`
- To seed the database from the command line
  `npm run seed`
- To start the application server
  `npm start`

Then open insomnia and test the Api Routes.

## Installation:

💾

- To install all file in order for npm to work
  `npm install`

- To create a json file
  `npm init`

- To connect to MySql database
  `npm install mysql2`

- To import Sequalize package to connect your Express.js API
  `npm install sequelize`

- To import dotenv package to use environment variables to store sensitive data, like your MySQL username, password, and database name
  `npm install dotenv`

## License:

This repository is licensed under the [MIT license](./LICENSE).

## Questions:

Please contact me at

- GitHub : [nkamth](https://github.com/nkamth)
- Email : [namitha.289@gmail.com](mailto:namitha.289@gmail.com)
