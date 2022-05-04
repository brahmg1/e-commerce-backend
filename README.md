# E-commerce Back End Starter Code

## Description

In this repository contains code for an E-commerce backend website.  The code creates a database and populates it with Categories, Products, and Tags.  In the API routes you can view the Cateogires, Products and Tags all at once or by an individual ID. Additionally, there are API routes to Create, Update, and Delete anything for the Categories, Products or Tags. This repository utilizes Express.js, MySQL2, Sequelize, and dotenv packages.

---

## Table of contents

* [Installation](#installation)
* [Questions](#questions)

---

## Installation and How to Use

Download or clone the codebase from github. You will need to have Node.js and MySQL installed as well. In the root directory of the project, find the ".env.EXAMPLE" file. Remove the ".EXAMPLE" from the name. Open up the .env file and input your MySQL Username, password, and ecommerce_db for the DB_NAME. At the root directory run "npm install" to install the necessary packages. To setup the database, launch your mysql shell from the root directory of the project and run "source db/schema.sql" to create the ecommerce_db. Quit out of the MySQL shell after this is done. At the root directory of the project run "npm run seed" to seed the database. Finally, run "npm start" to launch the server. With the server running you are able to execute any of the routes created to interact with the database.

---

## Walkthrough Video
[Walkthrough Video](https://drive.google.com/file/d/1RjuORoymj46LqD5AR3raRE6D_vv5B4zL/view)

---

## Questions

If you have any further questions or inquieres about the repository feel free to open an issue.

---