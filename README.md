# BMICalculator

BMICalculator is a web application that allows users to calculate their Body Mass Index (BMI) based on their height, weight, age, gender, and preferred unit system (metric or imperial). The application also provides a history feature to view past BMI calculations.

Disclaimer: The Body Mass Index (BMI) information provided in this project is sourced from the Nivea website's BMI calculator, accessible at https://www.nivea.ru/advice/calculator-bmi.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Dependencies](#dependencies)

## Installation

1. Clone the repository to your local machine.

    ```bash
    git clone https://github.com/aknietmaulen/BMI.git
    ```

2. Navigate to the project directory.

    ```bash
    cd BMI
    ```

3. Install the required npm packages.

    ```bash
    npm install
    ```

## Usage

1. Start the server.

    ```bash
    npm start
    ```

2. Open your web browser and go to `http://localhost:3000`.

## Features

### Calculate BMI

Click on "Calculate BMI" in the navigation to access the BMI calculator. Enter your details, choose the unit system, and click "Calculate" to see your BMI and category.

### What is BMI

Click on "What is BMI" in the navigation to learn more about BMICalculator and its purpose.

### Contacts

Click on "Contact" in the navigation to get contacts.

## Dependencies

- [Express](https://www.npmjs.com/package/express): Fast, unopinionated, minimalist web framework for Node.js.
- [Body-parser](https://www.npmjs.com/package/body-parser): Parse incoming request bodies in a middleware before your handlers, available under the req.body property.
- [Dotenv](https://www.npmjs.com/package/dotenv): Dotenv is a zero-dependency module that loads environment variables from a .env file into process.env.
