# E-Commerce Back End

## Description

This is a project made to display, create, adjust, and/or delete data for a e-commerce company. This uses express, mysql, and sequelize to reach these objectives and insomnia is used to perform our get/put/post/delete requests. This program was made to demonstrate my ability to develop and execute these requests that will be very necessary daily in my career going forward.

## Table of Contents

- README file
- server.js: the base file to run the server
- package/packagelock.json: the npm packages used for this project
- seeds folder: holds all the base data to be put into the database, with an index.js file used to run the seeding of the other files
- routes folder: contains the api folder, which holds all the routing data to use the get/put/post/delete requests for each section (tags/products/categories). proper routing is included on the index.js file for each folder.
- models folder: contains the table formatting for each table (tags/products/categories/product tags) as well as setting relationships between the tables in the index file
- db folder: schema to create our database, or delete if it exists and then recreate
- config folder: contains the file used to connect to the database using sequelize

## Links
[Recording of program in use]()