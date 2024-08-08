# E-Commerce_Back_End 🧑🏽‍💻

A back end for an e-commerce site. Working with Express.js API and configure it to use Sequelize to interact with a PostgreSQL database.

## User Story
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies

## Acceptance Criteria
GIVEN a functional Express.js API
- It's done WHEN I add my database name, PostgreSQL username, and PostgreSQL password to an environment variable file, THEN I am able to connect to a database using Sequelize

- It's done WHEN I enter schema and seed commands, THEN a development database is created and is seeded with test data.

- It's done WHEN I enter the command to invoke the application, THEN my server is started and the Sequelize models are synced to the PostgreSQL database

- It's done WHEN I open API GET routes in Insomnia Core for categories, products, or tags, THEN the data for each of these routes is displayed in a formatted JSON

- It's done WHEN I test API POST, PUT, and DELETE routes in Insomnia Core, THEN I am able to successfully create, update, and delete data in my database.

## Mock-Up
The following animations show examples of the application's API routes being tested in Insomnia Core.

### The first animation shows GET routes to return all categories, all products, and all tags being tested in Insomnia Core:
![](./13-orm-homework-demo-01.gif)


### The second animation shows GET routes to return a single category, a single product, and a single tag being tested in Insomnia Core:
![](./13-orm-homework-demo-02.gif)


### The final animation shows the POST, PUT, and DELETE routes for categories being tested in Insomnia Core: 
![](./13-orm-homework-demo-03.gif)

© 2024 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.