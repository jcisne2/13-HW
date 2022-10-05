## E-Commerce Backend

## Screencastify

https://drive.google.com/file/d/1djHyJdEZdK5UXrY3zi9rOmvKAu465z72/view

## Github URL 🌐
https://github.com/jcisne2/13-HW

## Table of Contents 🗒

* [User Story](#User-Story)

* [Acceptance Criteria](#Acceptance-Criteria)

* [Images](#images)

* [Installations](#dependencies)

* [Usage](#Usage)

* [Technology](#Technology)

* [Contributors](#contributors)

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

## Images

![mysql](https://user-images.githubusercontent.com/108189023/193993012-9acf2b04-0bcc-4cb6-8a3d-eed3581e5945.png)

![Tags](https://user-images.githubusercontent.com/108189023/193993022-98df9c8d-372a-4fae-a1a5-e72272c7f678.png)

![Product](https://user-images.githubusercontent.com/108189023/193993032-f3254612-234a-48d1-a4a9-6beafb3cdf6c.png)

![Categories](https://user-images.githubusercontent.com/108189023/193993042-843f2a7d-c4d1-4268-8375-e1273e71556c.png)

## Installations (Dependencies) 💻

To install dependencies, run these commands:

```
npm i

npm install mysql2

npm install sequelize

npm install dotenv

```

## Usage (Usage)

```
mysql -u root -p

type password

source db/schema.sql

quit

npm run seed

npm start

```

## Technology used

MYSQL

MySQL2 

Express

Sequelize 

dotenv.

## Contributors 😃

Jcisne2

Contact me at Cisnejos000@gmail.com
