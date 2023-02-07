# backend-ecommerce

## Description

User Story
```
AS A manager at an internet retail company

I WANT a back end for my e-commerce website that uses the latest technologies

SO THAT my company can compete with other e-commerce companies

```

Acceptance Criteria

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


## Installation

Run npm install to install the dependencies.

```npm run seed``` to seed the database

```npm start``` to start the server

Follow this link to the [Video Demo](https://youtu.be/Tx2Gni-mRbo)

## Usage


Retrieve all categories from the database
![Get request for categories](./Develop/assets/Screenshot%202023-02-06%20at%2011.46.56%20PM.png)

Retrieve all products from the database
![Get request for products](./Develop/assets/Screenshot%202023-02-06%20at%2011.46.32%20PM.png)

Retrieve all tags from the database
![Get request for tags](./Develop/assets/Screenshot%202023-02-06%20at%2011.47.02%20PM.png)

Post Request
![Post Request](./Develop/assets/Screenshot%202023-02-06%20at%2011.47.17%20PM.png)

Put Request
![Put Request](./Develop/assets/Screenshot%202023-02-06%20at%2011.47.11%20PM.png)

Delete Request
![Delete Request](./Develop/assets/Screenshot%202023-02-06%20at%2011.47.24%20PM.png)

## License

MIT License

Copyright (c) [2023] [Jasmine Ulloa]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Badges


![MySql](https://img.shields.io/badge/MySQL-4479A1.svg?style=for-the-badge&logo=MySQL&logoColor=white)


![Javascript](https://img.shields.io/badge/JavaScript-F7DF1E.svg?style=for-the-badge&logo=JavaScript&logoColor=black)

![Express](https://img.shields.io/badge/Express-000000.svg?style=for-the-badge&logo=Express&logoColor=white)