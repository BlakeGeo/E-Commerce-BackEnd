
<h1 align="center">E-Commerce Back End</h1>
   
  
<p align="center">
    <img src="https://img.shields.io/github/repo-size/BlakeGeo/E-Commerce-BackEnd" />
    <img src="https://img.shields.io/github/languages/top/BlakeGeo/E-Commerce-BackEnd"  />
    <img src="https://img.shields.io/github/issues/BlakeGeo/E-Commerce-BackEnd" />
    <img src="https://img.shields.io/github/last-commit/BlakeGeo/E-Commerce-BackEnd" >
</p>
  
<p align="center">
    <img src="https://img.shields.io/badge/Javascript-yellow" />
    <img src="https://img.shields.io/badge/VisualStudioCode-blue"  />
    <img src="https://img.shields.io/badge/-Node.js-green" />
    <img src="https://img.shields.io/badge/-Express-red" >
    <img src="https://img.shields.io/badge/-Screencastify-lightgrey" />
    <img src="https://img.shields.io/badge/-MySQL-orange" />
    <img src="https://img.shields.io/badge/-Sequelize-brightgreen" />

</p>
   
## Description
  
🔍 A node.js backend app that allows you to view, update, add and delete all products within the ecommerce database using a program such as Insomnia or Postman.
  
💻 Below is a gif showing the functionality of the application:
  
![E-Commerce Back End](assets/E-Commerce-BackEnd.gif)
  
🎥 The full movie file showing functionality of the application can be found [here](https://drive.google.com/file/d/1SuVSUW7iq2b6QOOWENxNhY681nqfS5YC/view)
  
## User Story
  
```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```
  
## Acceptance Criteria
  
``` 
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
  
## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Contact](#contact)

## Installation
💾 Run the following commands to install this application:

To install all packages required:

`npm i`

Add database (within mysql shell inside the db folder):

`source schema.sql`

To seed all data:

`npm run seed`
  
## Usage
💻 Run the following command at the root of your project to gain access to the server and all requests:

`node server.js`

## Contributing
[Blake Georgeff](https://github.com/BlakeGeo)

## Contact
✉️ Contact me with any questions: [email](mailto:georgeffb@hotmail.com) , [GitHub](https://github.com/BlakeGeo)<br />

    