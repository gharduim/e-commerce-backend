# E-commerce-backend

## Description

A mysql database and application backend for an e-commerce site. Built using MySQL2, Express, Sequelize and dotenv.

## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```md
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
```

### Demonstration

View a complete video demonstration of the application: [E-commerce backend Demo](https://drive.google.com/file/d/19N-MUhK5rrgezrrgeRvDcBXDMwEuiggz/view?usp=sharing)

 [E-commerce backend - Categories](https://drive.google.com/file/d/1wL3jmsuRc4dkLfjObfUrUssTkE9n3kTd/view?usp=sharing)
 [E-commerce backend - TAGS](https://drive.google.com/file/d/11tCU2fX876ae57ucQ43X2Ty7s6rRkyJ6/view?usp=sharing)

![E-commerce-screen](./videos/.gif "E-commerce backend")

## Table of Contents

* [Description](#description)
* [User Story](#user-story)
* [Acceptance Criteria](#acceptance-criteria)
* [Technologies](#technologies)
* [Installation](#installation)
* [Usage](#usage)
* [Questions](#questions)

## Technologies

* [Node.js](https://nodejs.org/)
* [Sequelize](https://sequelize.org/)
* [MySQL](https://www.mysql.com/)

## Installation

To install dependencies, run the following:

`npm init`

`npm install mysql2`

`npm install sequelize`

`npm install dotenv`
  

## Usage

After installing the dependencies, run the application with

`mysql -u root -p`

Enter PW when promted

`source db/schema.sql`

`quit`

`npm run seed`
  
`npm start`

## Questions

Questions about this repository? Please contact me at [gharduim@gmail.com](mailto:gharduim@gmail.com). View more of my work in GitHub at [Gustavo Harduim](https://github.com/gharduim) 
