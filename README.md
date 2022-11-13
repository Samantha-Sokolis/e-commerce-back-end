# E-commerce Back End

## Description
This project entailed a build of the back end for an e-commerce site, with Express.js API configured to use Sequelize to interact with a MySQL database. The purpose behind this project is to understand the fundamental architecture of e-commerce sites, since it is the largest sector of the electronics industry. 

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


## Installation

mysql -u root -p

Enter PW when promted

source db/schema.sql

quit

npm run seed

npm start


## Walkthrough Videos

1. Video 1 shows mysql Database created:
https://watch.screencastify.com/v/PnCAZVAOhD9t1HcXfYNK


