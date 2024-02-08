# Application Setup and Testing

This document provides instructions on how to set up and test the application.

## Table of Contents

- [Installation](#installation)
- [Running the Application](#running-the-application)
- [API Endpoint](#api-endpoints)
- [Running Tests](#running-tests)


## Installation

Follow these steps to install the application:

1. Clone the repository:

   ```bash
   git clone https://github.com/bcgru/kanye-api.git
2. Navigate to the project directory:

    ```bash
    cd your-repo
3. Install the required dependencies using Composer:

    ```bash
    composer install
## Running the Application

To run the application, execute the following command:
    ```bash
    php artisan serve

This will start a development server, and you can access the application in your browser at http://localhost:8000.

## API Endpoints
The application provides the following API endpoints:

- GET `/api/quotes`: Fetches a random selection of quotes from Kanye West.
- GET `/api/quotes/refresh`: Refreshes the cache of quotes from Kanye West.

To access the API endpoints, you can use tools like cURL or HTTP clients like Postman.

## Running Tests
The application comes with a suite of unit and feature tests. To run the tests, use the following command:

    php artisan test
    php artisan test --testsuite=Feature
    php artisan test --testsuite=Unit

This will execute all the tests and display the results in the console.
