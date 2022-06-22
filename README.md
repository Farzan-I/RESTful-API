# RESTful API using Node, Express and MongoDB

## Introduction
Using the [guide](https://www.freecodecamp.org/news/build-a-restful-api-using-node-express-and-mongodb/) provided on free code camp, I built a RESTful API using Node, Express and MongoDB. I created endpoints for creating data, reading data, updating data and deleting data (basic CRUD operations).

## Set-up
* In an empty folder, I ran the following command: `npm init -y`
* This command will generate a **package.json** file in the designated folder, which contains all the scripts i.e. how to run the app or how to test the app as well as all the dependencies
* To install the dependencies, run `npm i express mongoose nodemon dotenv`

## Use of this repository
* Type `npm start` to run the server (port is currently 3000)
* The server is not live for all to use, so you will need to create a cluster locally with MongoDB
* Use Postman to send get, post, patch and delete requests (CRUD operations)

## MongoDB Compass
I created a new account on the [MondoDB website](https://account.mongodb.com/account/login) which hosts a database (similar to [TablePlus](https://tableplus.com/)). Here it was very easy to get started and I'd recommend this over TablePlus as it provides a clear view of all the data and objects you have saved in your database. Instructions for getting started on the website can be found on the guide provided in the introduction.

## Postman
This is a great tool to test API endpoints. [Postman](https://www.postman.com/) is free to use and very easy to navigate through. The guide for installing this can also be found later on in the guide (provided in the introduction). Only part that it did not specify is the fact that we need to change the drop down menu from text to JSON format. This is essential if you want to follow the guide like myself and get stuck.