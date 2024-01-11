# Metric-Imperial Converter 📏🔄

This project is a web application that allows users to convert between different units of measurement, such as miles and kilometers, pounds and kilograms, gallons and liters, etc.

The project is part of the freeCodeCamp curriculum for the Quality Assurance certification. It demonstrates the use of Node.js, Express, Chai, Mocha, and Helmet.

## Installation ⚙️

To run this project locally, you need to have Node.js and npm installed on your machine. Then follow these steps:

- Clone this repository to your local machine.
- Navigate to the project folder and run `npm install` to install the dependencies.
- Run `npm start` to start the server.
- Open your browser and go to `http://localhost:3000` to view the application.

## Usage 🖱️

The application has a simple user interface that consists of a form and a result area. To use the application, follow these steps:

- Enter a number and a unit in the form, such as `10 mi` or `3 kg`.
- Click the `Convert` button to submit the input.
- The result area will display the converted value and the unit, such as `16.09344 km` or `6.61387 lbs`.
- You can also use the URL to make conversions, such as `http://localhost:3000/api/convert?input=10mi` or `http://localhost:3000/api/convert?input=3kg`.

## Testing 🧪

The project includes a set of unit and functional tests that can be run using Mocha and Chai. To run the tests, follow these steps:

- Run `npm run test` to start the testing process.
- The test results will be displayed in the console.
- You can also view the test coverage report by opening the `coverage/index.html` file in your browser.
