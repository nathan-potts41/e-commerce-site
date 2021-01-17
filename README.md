# E-Commerce Back End
## Description 

An Express.js app that makes MySQL database calls that an e-commerce site could use to keep track of their stock and populate their pages for their customers to view their products.

---

## Table of Contents 

- [Built With](#built-with)
- [Installation](#installation)
- [Usage](#usage)
- [Contributors](#contributors)
- [Acknowledgements](#acknowledgements)

---

## Built With

![JavaScript](https://img.shields.io/badge/javascript%20-%23323330.svg?&style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![node.js](https://img.shields.io/badge/node.js%20-%2343853D.svg?&style=for-the-badge&logo=node.js&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?&style=for-the-badge&logo=mysql&logoColor=white)


---
## Installation
### Requirements
- Node.js
- MySQL

Installation requires cloaning the repo. Aftwards run npm install. That will give you all of the dependencies.


[Back to Contents](#table-of-contents)

---

## Usage

[Video Tutorial](https://drive.google.com/file/d/1orpr37u54CARbxmx5lLGG3WpO5tqO6Cu/view?usp=sharing)

It is recommended that you install dotenv from node to make your private information confidential. Add the following to your .env file:

DB_NAME='ecommerce_db'

DB_USER='*Your MySQL Username*'

DB_PW='*Your MySQL Password*'

Link the .env file to your database by requiring the information in your connection.js file located in the config directory. Proceed to the MySQL terminal, entering your password to gain access. From here, run the command 'source db/schema.sql'. Once you've recieved confirmation you may exit back to your original terminal. Seed the database by running the command 'npm run seed'. To run the server, type the command 'npm start'.

Use the video tutorial at the top of this section if you have any questions.

[Back to Contents](#table-of-contents)
  
---

## Contributors
Jake Nystrom
Craig Bennett

---
---

[Back to Contents](#table-of-contents)

---


[Back to Contents](#table-of-contents)