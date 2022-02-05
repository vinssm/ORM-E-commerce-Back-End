# ORM-E-commerce-Back-End

## This challenge is to build the back end for an e-commerce site, which will be using Express.js API and configure it using Sequelize to interact with MySQL database.

## User Story
- AS A manager at an internet retail company
- I WANT a back end for my e-commerce website that uses the latest technologies
- SO THAT my company can compete with other e-commerce companies

## Acceptance Criteria
- GIVEN a functional Express.js API
- WHEN I add my database name, MySQL username, and MySQL password to an - - environment variable file
- THEN I am able to connect to a database using Sequelize
- WHEN I enter schema and seed commands
- THEN a development database is created and is seeded with test data
- WHEN I enter the command to invoke the application
- THEN my server is started and the Sequelize models are synced to the MySQL database
- WHEN I open API GET routes in Insomnia for categories, products, or tags
- THEN the data for each of these routes is displayed in a formatted JSON
- WHEN I test API POST, PUT, and DELETE routes in Insomnia
- THEN I am able to successfully create, update, and delete data in my database

## Dev Steps 
- Clone Repo 
- install packages using npm install 
- create .env file and add DB_NAME; DB_USER; DB_PW
- In the address bar of the project folder type cmd to open terminal and enter mysql -u root -p
- Enter Password to login to SQL shell
- Source the DB using source db/schema.sql
- Now in the GIT Bash Terminal seed the database
- Enter npm run seed
- Then follwed by pm start to start the server 
- Once success message appears, open Insomnia / Postman 
- Then test it by GET, POST, PUT and DETELE routes 

* [DEMO LINK](https://www.youtube.com/watch?v=ZkEDz5qmx3c)