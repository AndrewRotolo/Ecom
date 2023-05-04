# Andrew Rotolo's E-Commerce Backend

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description
Backend framework for managing product inventory in a retail environment via a MySQL database.

## Installation
This application requires no direct installation beyond downloading the raw files, but it does require node.js and MySQL to be installed on your system in order to function. Additionally, it utilizes several dependencies that can be installed via the "npm install" command in node.js.

## Usage
Please note that this application was created for educational purposes and has no frontend components. As such, there are no practical use cases for this software in its current state. However, you are free to test the various GET, POST, PUT, and DELETE routes in the web development tool of your choice (Andrew used Insomnia). But before testing, you should run the provided schema in your MySQL workbench and seed the new database with the "npm run seed" command in the terminal.

Please refer to the following video demonstration:
https://www.youtube.com/watch?v=E4_gyybqK7U

## Known Issues
-The application has no frontend components and that is unlikely to ever change
-The ProductTag Sequelize through model is not working properly, which breaks some of the Product and Tag routes

## Credits
This software was created using starter code provided by Rutgers University Coding Bootcamp

## License
Software provided under the MIT License. Please refer to the included license file for more details.