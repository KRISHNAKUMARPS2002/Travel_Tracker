# Travel Tracker

Travel Tracker is a web application built with Express.js and PostgreSQL that allows users to track the countries they have visited.

## Features

- Add countries you have visited.
- View the total number of countries visited.
- Search and select countries from a predefined list.

## Prerequisites

- Node.js installed on your machine
- PostgreSQL database setup with the appropriate schema
- Express.js and necessary dependencies installed (You can run `npm install` to install dependencies)

## Getting Started

1. Clone this repository to your local machine.
2. Navigate to the project directory in your terminal.
3. Install dependencies using `npm install`.
4. Create a `.env` file in the root directory and add your PostgreSQL database credentials:

- DB_USER=your_postgres_username
- DB_PASSWORD=your_postgres_password
- DB_HOST=localhost
- DB_PORT=5432
- DB_NAME=world


5. Run the database migration scripts to set up the necessary tables (`countries` and `visited_countries`).
6. Start the Express server using `npm start`.
7. Access the application in your web browser at `http://localhost:3000`.

## Usage

- Enter a country name in the input field and click the "Add" button to mark it as visited.
- The total count of visited countries will be displayed on the homepage.
- You can search for countries from the predefined list and add them to your visited countries list.


