# E-Commerce Back End

## Description

A Sequelize and MySQL2 backend database mock-up for e-commerce

---

## Installation

To install the application you'll need to do the following:

- Clone the repository to your local machine
- Navigate to the project repository
- Type `npm install` in the terminal to install dependencies
- Log in to MySQL in your terminal
- Run the command `source db/schema.sql` to create the database, then exit the MySQL shell by typing `exit` in your terminal
- Run the command `npm run seed` to seed the database using the files within the ./seeds folder
- Run the command `npm run watch` to start the local server

---

## Usage

A short video demonstration can be found here: NOT YET IMPLEMENTED

After the necessary dependencies have been installed, you have created and seeded the database, and you have started the local server by running the `npm run watch` command you can view various tables and their corresponding foreign keys using an API development platform like Insomnia, Postman, or other alternatives.

---

You can perform a Get operation to display all items in a given category, all products, or all tags. You can also search by a specific ID by performing the same Get operation with the id you wish to search for as the endpoint.

![Get All](./assets/images/READMEGIF-GetAll.gif)

You can perform a Post operation to create a new category, product, or tag. You can also update an items name by ID, as well as delete an item by ID.

!![Delete Item](./assets/images/READMEGIF-DeleteCat.gif)

---

## Technologies



---