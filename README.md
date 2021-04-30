# e-commerece-backend

## Description 

![screenshot](assets/ecommerece_demo.gif)

E-commerece back-end framework. Easily organize your products by categories and tags. Products, Tags and Categories can be edited and assigned as needed to ensure your inventory is properly maintained and accounted for. 

[GitHub Repo](https://github.com/iandarland/e-commerece-backend)

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Testing](#testing)
- [Questions](#questions)
## Installation

- Node
- sequelize
- express
- mySql workbench

## Usage

create a .env file and insert the appropriate information. DB name "ecommerce_db" as below
```
DB_USER=root
DB_PW=root
DB_NAME=ecommerce_db
```
Next ensure all dependencies are downloaded by running npm i in the terminal. Next run "npm run seed" to ensure the database is seeded. finally run "npm start" to deploy the server. see commands below.
```
npm i
npm run seed
npm start
```

Now use insomnia or post man to send get, post, put and delete routes to the routes below. Include id numbers in route to target individual rows. 
```
http://localhost:3001/api/Products/
http://localhost:3001/api/Tags/
http://localhost:3001/api/Categories/
```

## Contributing

Ian Darland

## Questions

Email: ianpdarland@gmail.com

[Github](www.github.com/iandarland)