# Tuck-E_Commerce-Back-End
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
## Description

This is a E-Commerce Back End to Get, Post, Put, and Delete inventory information on a database via API endpoints.

## Table of Contents

[Installation](#Installation)
[Usage](#Usage)
[License](#License)
[Questions](#Questions)

## Installation

Download and install [Node.js LTS](https://nodejs.org/en/download/) if not already installed<br/><br/>Fork this [repo](https://github.com/jamesjtuckbc/Tuck-E_Commerce-Back-End) and then clone<br/>`git clone git@github.com:EnterYourGitHubUserName/Tuck-E_Commerce-Back-End.git && cd Tuck-E_Commerce-Back-End`<br/><br/>Install dependencies<br/>`npm i`<br/><br/>Setup Database for use in MySQL<br/>`DROP DATABASE IF EXISTS ecommerce_db;`<br/>`CREATE DATABASE ecommerce_db;`<br/><br/>Run the application<br/>`npm start`<br/><br/>

## Usage
GET Tags - `GET - /api/tags`
GET Tags by ID - `GET - /api/tags/:id`
CREATE Tags - `CREATE - /api/tags`
UPDATE Tags by ID - `UPDATE - /api/tags/:id`
DELETE Tags by ID - `DELETE - /api/tags/:id`
GET Products - `GET - /api/products/`
GET Products by ID - `GET - /api/products/:id`
CREATE Products - `CREATE - /api/products/`
UPDATE Products by ID - `UPDATE - /api/products/:id`
DELETE Products by ID - `DELETE - /api/products/:id`
GET Categories - `GET - /api/categories/`
GET Categories by ID - `GET - /api/categories/:id`
CREATE Categories - `CREATE - /api/categories/`
UPDATE Categories by ID - `UPDATE - /api/categories/:id`
DELETE Categories by ID - `DELETE - /api/categories/:id`

See example gif for usage via Insomnia:
![example gif](./assets/e-commerce.gif)

## License

This work is covered under [The MIT License](https://opensource.org/licenses/MIT)

## Questions

Please reach-out to me on [GitHub](http://www.github.com/jamesjtuckbc) or email me at: [jamesjtuck@gmail.com](mailto:jamesjtuck@gmail.com)

---
© 2020 Jorgen Tuck